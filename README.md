Deprecated
==========

**This role is deprecated. Please use the role [f500.php7](https://github.com/f500/ansible-php7), v1.0.0 or higher.**

---

PHP7_DEV
========

Install latest PHP (development package) version in DotDeb repository

Requirements
------------

Debian Jessie with the package python-pycurl and python-software-properties installed.

Example Playbook
-------------------------

    - hosts: servers
      roles:
        - { role: f500.php7_dev }

License
-------

Copyright (C) 2017 Future500 B.V.

[LGPL-3.0](https://github.com/f500/ansible-php7_dev/blob/master/COPYING.LESSER)

Author Information
------------------

Jasper N. Brouwer, jasper@future500.nl

Ramon de la Fuente, ramon@future500.nl
