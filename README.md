hemanth22.rhelupgradechecks
=========

This role created to perform rhel upgrade checks using rundeck.

Requirements
------------

Ensure cronie, sudo is installed.

Role Variables
--------------



Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
---
- hosts: localhost
  remote_user: root
  roles:
    - hemanth22.rhelupgradechecks
      vars:
        prefix: "pre"
```

License
-------

GPL-3.0-only

Author Information
------------------

This role was created in 2025 by Hemanth BITRA. Author Website: bitroid.in
