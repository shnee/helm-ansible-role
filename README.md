Role Name
=========

An Ansible role to install helm.

Requirements
------------

None

Role Variables
--------------

```yml
helm_version: 3.7.2
helm_arch: amd64
```

Dependencies
------------

None

Example Playbook
----------------

```yml
- name: Install helm.
  hosts: all
  roles:
    - { role: install_helm, helm_version: 3.7,2, helm_arch: amd64 }
```

License
-------

MIT

Author Information
------------------

This role was created by [shnee](https://github.com/shnee).
