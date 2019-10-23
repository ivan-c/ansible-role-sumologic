Ansible Role: Sumo Logic hosted collector
=========
Manage rsyslog configuration for Sumo Logic centralized logging

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
