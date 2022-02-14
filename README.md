pbos.cinder
==============

Ansible role to install and setup Cinder for OpenStack.

Cinder is a volume service for instances.

Requirements
------------

This role requires Ansible 2.11 or higher.

This role supports:

  - Rocky Linux 8.x

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    hosts: servers
    roles:
      - { role: pbos.cinder, tags: cinder }

Cinder is installed on the node in cinder inventory group:

    [cinder]
    host-1
    host-2
    host-3

License
-------

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

  - Heechul Kim @iOrchard
      - <https://github.com/iorchard>

