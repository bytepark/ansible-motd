ansible-motd
=========

Ansible role to install a MOTD showing information that the system is ansible managed

Requirements
------------

No further requirements besides bash.

Role Variables
--------------

motd_contact_email - email address to display 

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: bytepark.motd }

License
-------

MIT

Author Information
------------------

bytepark / 2018.

