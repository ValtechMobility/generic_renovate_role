Renovate
=========

A role to create a cronjob to periodically run renovate in a docker container.

Requirements
------------

- Docker

Role Variables
--------------

For all variables please see `defaults/main.yml`.


Dependencies
------------

None

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - generic_renovate_role