Ansible do-agent role
=========
[![Build Status](https://travis-ci.org/andrewsomething/ansible-role-do-agent.svg?branch=master)](https://travis-ci.org/andrewsomething/ansible-role-do-agent) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-andrewsomething.do--agent-blue.svg)](https://galaxy.ansible.com/andrewsomething/do-agent/)

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