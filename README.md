Ansible Role: Install Let's Encrypt + Automatic certificates renewal
=========

This role installs Let's Encrypt and setup a cron job to automate the renewal of all SSL certificates.

Requirements
------------

No specific requirements for this role.

Role Variables
--------------

No variables for this role.

Dependencies
------------

No dependencies from other roles required.

Example Playbook
----------------

Here is a simple example playbook to use this role:

```
hosts: all
user: myuser
become: true
roles:
  - { role: letsencrypt, tags: [ 'letsencrypt' ] }
```

License
-------

MIT / BSD

Author Information
------------------

My name is Gaétan. You can follow me on [Twitter](https://twitter.com/gaetanict)

Website: [ICT Pour Tous](https://www.ictpourtous.com)
