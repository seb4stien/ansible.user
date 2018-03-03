ansible.ssh-user
================

Add a user with an authorized key

Variables
---------

- username 
- add_in_sudoers: to add no passwd sudo (default = false)
- 'key' in files/keys/id_rsa.$username.pub
