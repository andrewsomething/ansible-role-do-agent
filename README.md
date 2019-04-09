Ansible do-agent role
=========
[![Build Status](https://travis-ci.org/andrewsomething/ansible-role-do-agent.svg?branch=master)](https://travis-ci.org/andrewsomething/ansible-role-do-agent) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-andrewsomething.do--agent-blue.svg)](https://galaxy.ansible.com/andrewsomething/do-agent/)

Role to install the [DigitalOcean monitoring agent](https://github.com/digitalocean/do-agent) on all supported distros. It will also [migrate from the legacy agent to the current one](https://www.digitalocean.com/docs/monitoring/how-to/upgrade-legacy-agent/).

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

https://blog.andrewsomething.com/
