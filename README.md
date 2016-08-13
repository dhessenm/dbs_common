Ansible role: dbs_common
=========

Role setup some basics on host

Requirements
------------


Role Variables
--------------

Available variables are listed below, along with default values:

* packages_debian: curl, jq

Dependencies
------------

* dbs_proxyconf


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dbs_common, tags ["commom"]  }

License
-------

BSD

Author Information
------------------
it's me
