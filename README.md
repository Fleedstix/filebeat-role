Filebeat role
=========

Роль для установки Filebeat на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| Filebeat_version | "7.14.0" | Параметр, который определяет какой версии Filebeat будет установлен |
| filebeat_install_type | remote/local | Параметр, который указаывает, будем ли мы качать пакет с сайта разработчика ( remote ), или же пакет уже подложен в директории files ( local ) 
Example Playbook | 
Example Playbook
----------------

    - hosts: all
      roles:
         - { role: mnt-homeworks-ansible }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
