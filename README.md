mamercad.zabbix-frontend
=========

Stands up Zabbix 3.0.0 (frontend) with MariaDB on RHEL/CentOS

Requirements
------------

None

Role Variables
--------------

The timezone for the zabbix frontend can be set in vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts: zabbix-frontend
      roles:
         - mamercad.zabbix-frontend

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
