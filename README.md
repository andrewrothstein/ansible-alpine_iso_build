andrewrothstein.alpine-iso-build
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-alpine-iso-build.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-alpine-iso-build)

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
