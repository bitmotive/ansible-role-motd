ansible-role-motd
=========

Configure a message of the day for servers

Requirements
------------

This role has only been tested on EL 6 systems.

Role Variables
--------------

__role\_motd\_message\__: The message to be displayed on login. May be customized per host or per group via host_vars or group_vars.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: bitmotive.ansible-role-motd, tags: "motd,common" }
```

License
-------

MIT
