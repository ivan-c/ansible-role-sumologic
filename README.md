Ansible Role: Sumo Logic hosted collector
=========
Manage rsyslog configuration for Sumo Logic centralized logging

![](https://github.com/ivan-c/ansible-role-sumologic/workflows/%E2%9A%9B%EF%B8%8FMolecule%20testing/badge.svg)

Role Variables
--------------
`sumologic_token` - Token provided by Sumo Logic for a hosted rsyslog collector

Example Playbook
----------------
    - hosts: centralized_logging
      roles:
         - { role: ivan-c.sumologic }

License
-------
BSD
