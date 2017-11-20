Role Name
=========

Ansible role to install and configure libvirtd

Requirements
------------

None

Role Variables
--------------
```yaml
libvirt_users: A LIST of users to add to the libvirtd group
```

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: username.rolename, x: 42 }
```

License
-------

GPLv3

Author Information
------------------

Brad Searle

