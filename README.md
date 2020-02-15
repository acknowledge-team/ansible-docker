Role Name
=========

This role is used to install docker on a unix host.
Currently only Debian is supported.

Requirements
------------

- Debian >= 9

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - ansible-docker
```