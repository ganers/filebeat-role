Filebeat role
=========

Роль для установки filebeat.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| filebeat_version | "7.14.0" | Параметр, который определяет какой версии filebeat будет установлен |

Example Playbook
----------------

    - hosts: app-instance
      roles:
         - { role: filebeat-role }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
