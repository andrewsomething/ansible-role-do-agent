Ansible do-agent role
=========
[![Build Status](https://travis-ci.org/andrewsomething/ansible-role-do-agent.svg?branch=master)](https://travis-ci.org/andrewsomething/ansible-role-do-agent)

Role to install the DigitalOcean monitoring agent on all supported distros.

Installation
------------

To install this role from Ansible Galaxy

    ansible-galaxy install andrewsomething.do-agent

Example Playbook
----------------

    - hosts: all
      become: true
      roles:
         - andrewsomething.do-agent

License
-------

MIT

Author Information
------------------

http://andrewsomething.com/