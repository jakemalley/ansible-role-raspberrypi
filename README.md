Ansible Role: Raspberry Pi
=========

A simple role for bootstrapping Raspberry Pis

(Based on the role by Jeff Geerling, available here: https://github.com/geerlingguy/ansible-role-raspberry-pi)

Requirements
------------

None

Role Variables
--------------

See: `defaults/main.yml`

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: pi
      roles:
         - { role: jakemalley.raspberrypi }

License
-------

MIT / BSD
