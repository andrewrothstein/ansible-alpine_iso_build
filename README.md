andrewrothstein.alpine-iso-build
=========
![Build Status](https://github.com/andrewrothstein/ansible-alpine-iso-build/actions/workflows/build.yml/badge.svg)

Builds Alpine Linux ISOs per [this](https://wiki.alpinelinux.org/wiki/How_to_make_a_custom_ISO_image_with_mkimage) document

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.alpine-iso-build
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
