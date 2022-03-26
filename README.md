logstash role
=========

Роль для установки logstash на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| logstash_version | "8.1.0" | Параметр, который определяет какой версии logstash будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: logstash_role }

License
-------

BSD


