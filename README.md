uclalib_role_redis
=========

Ansible role to install Redis on a RHEL8 system.

Requirements
------------

None.

Role Variables
--------------

# Must be a version available in a RHEL8 module
# For RHEL8 valid options are: "5" or "6"
* `redis_version` - defines the version of redis to install; must be a version available in a RHEL8 module (e.g. `5` or `6`)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: uclalib_role_redis }
