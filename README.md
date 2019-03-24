Preprovision
====

Install common packages.

Requirements
-------------

This role requires ansible 1.4 or higher.

Role Variables
--------------

Dependencies
------------


Example Playbook
----------------

```
---
- hosts: all
  become: True
  roles:
    - { role: 1mr.preprovision, tags: preprovision }

```

License
-------

BSD

Author Information
------------------

Created by Stas Stavnichuk 
