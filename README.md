
Ansible-role-user
=======

ansible repo for Create multiple users

Role Variables
--------------
    users:
     - username: joy
       use_sudo: no
      
     - username: alex
       use_sudo: yes
Dependencies
------------

- install ansible
- create keys
- configure client server authorized_keys

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-user,                      tags: [ 'user' ] }
tested
--------------
Currently, this is only tested on Ubuntu 18.02 as a client and server machine. It should theoretically work on older versions of Ubuntu or Debian based systems.

License
-------
BSD

## 👬 Contribution
- Open pull request with improvements
- Discuss ideas in issues

- Reach out with any feedback [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/anmol_nagpal.svg?style=social&label=Follow%20%40anmol_nagpal)](https://twitter.com/anmol_nagpal)
=======

