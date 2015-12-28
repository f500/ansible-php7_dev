php_dev
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

LGPL

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
