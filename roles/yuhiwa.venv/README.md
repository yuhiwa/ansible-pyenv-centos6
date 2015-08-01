Ansible Role: Python
====================

Installs minimal Python 2.7.x + Setuptools + PIP (from package) on CentOS 6.x

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

* yuhiwac6.yum

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: yuhiwa.venv}

License
-------

BSD

Author Information
------------------

This role was created by [Yuki Iwamoto](http://yuhiwa.github.io)
