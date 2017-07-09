[![Build Status](https://travis-ci.org/AAROC/glibrary-role.svg?branch=master)](https://travis-ci.org/AAROC/glibrary-role)

gLibrary
=========

This role deploys  and configures a gLibrary instance which can be configured for various types of storage. This role is not container-enabled but should work in a container environment.t

Requirements
------------

The role requires `git` and `node`

Role Variables
--------------

Variables are split between `main.yml`, `passwords.yml` and `defaults.yml`.
Passwords are included in a task, and vault-encrypted.


Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: AAROC.glibrary }

License
-------

Apache-2.0

Author Information
------------------

Written by Bruce Becker, CSIR Meraka Institute, for Africa-Arabia Regional Operations Centre.
