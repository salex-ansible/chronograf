Ansible Chronograf (Influxdata) role
=========

Simple role that installs Chronograf on your server.

Requirements
------------

Ansible 2.0 and Ubuntu on the server.

Role Variables
--------------

Chronograf package URL:

`chronograf_deb_url: https://dl.influxdata.com/chronograf/releases/chronograf_1.3.3.0_amd64.deb`

This role has no configuration files.

Dependencies
------------
No

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: salex-ansible.chronograf }

License
-------

BSD

