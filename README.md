kubectl
=======

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-kubectl.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-kubectl)

Use this role to install kubectl.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    kubectl_version: v1.18.3 # defaults to 'latest'

Example Playbook
----------------

    - hosts: kubectl
      roles:
         - andrelohmann.kubectl

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
