ageres210784/ansible_gitlab
=========

An Ansible role which installs [gitlab] on Linux docker

Requirements
------------

Ansible 2.9+

Role Variables
--------------

You can see all vars in `defaults/main.yml` vars file.

Dependencies
------------

`sorrowless/docker`

Example Playbook
----------------

    - name: Ensure gitlab
      hosts: gitlab_hosts
      remote_user: root

      roles:
         - { role: ageres210784.ansible_gitlab, tags: ['gitlab'] }

License
-------

Apache 2.0

Author Information
------------------

This role was created by [Sergey Evseev].
