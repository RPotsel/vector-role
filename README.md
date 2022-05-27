Vector
=========

Homework 08-ansible-04-role.

Requirements
------------

There are no requirements.

Role Variables
--------------

Look at defaults/main.yml

Dependencies
------------

There are no dependencies.

Example Playbook
----------------

```YAML
- name: Requirements for Vector
  src: git@github.com:Rpotsel/vector-role.git
  scm: git
  version: "1.1"
  name: vector

- name: Install Vector
  roles:
    - vector
```

License
-------

MIT

Author Information
------------------

Netology DevOps-14 Student.
