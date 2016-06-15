Debian-Certbot
==============

Automatically enable HTTPS on your website with EFF's Certbot, deploying Let's Encrypt certificates.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-certbot }

Tasks
-----

  - Install [certbot](https://certbot.eff.org/) command
  - Setup the renew cron task

License
-------

BSD
