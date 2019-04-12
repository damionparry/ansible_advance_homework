app-tier
=========

Role to install tomcat and copy over a basic index.html template

Requirements
------------

N/A

Role Variables
--------------

packages: name of the packe to install (tomcat)
tomcat_root: location of the tomcat root folder

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: apps
      roles:
         - { role: app-tier, packages: tomcat, tomcat_root: /usr/share/tomcat/webapps/ROOT }

License
-------

BSD

Author Information
------------------

Written for the Red Hat Advanced Ansible Bootcamp
