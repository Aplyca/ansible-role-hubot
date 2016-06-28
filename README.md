Ansible Role: Hubot
==========================

[![Build Status](https://travis-ci.org/Aplyca/ansible-role-hubot.svg?branch=master)](https://travis-ci.org/Aplyca/ansible-role-hubot)
[![Circle CI](https://circleci.com/gh/Aplyca/ansible-role-hubot.png?style=badge)](https://circleci.com/gh/Aplyca/ansible-role-hubot)

Ansible Role that installs an configure Hubot on Debian/Ubuntu.

Requirements
------------

Use hash behavior for variables in ansible.cfg
See example: https://github.com/Aplyca/ansible-role-hubot/blob/master/tests/ansible.cfg
See official docs: http://docs.ansible.com/intro_configuration.html#hash-behaviour

Installation
------------

Using ansible galaxy:
```bash
ansible-galaxy install aplyca.Hubot
```
You can add this role as a dependency for other roles, add the role to the meta/main.yml file of your own role:
```yaml
dependencies:
  - { role: aplyca.Hubot }
```

Role Variables
--------------

See default variables: https://github.com/Aplyca/ansible-role-hubot/blob/master/tests/tests.yml

Dependencies
------------

None.

Testing
-------
Using Vagrant:

```bash
tests/vagrant.sh
```
Using Docker:

```bash
tests/docker.sh
```

License
-------

MIT / BSD

Author Information
------------------

Mauricio Sánchez from Aplyca SAS (http://www.aplyca.com)
