lb-tier
=========

A role to install and configure ha-proxy to load balance across all app servers

Requirements
------------

Requires a host group call apps

Role Variables
--------------

packages variable defined in vars/main.yml contains package names to be installed

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: apps
      roles:
         - { role: lb-tier, packages: haproxy }

License
-------

BSD

Author Information
------------------

Written for the Red Hat Advanced Ansible Bootcamp
