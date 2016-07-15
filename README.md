Role Name
=========

Installs Docker on Ubuntu 16.04

Requirements
------------

Requires Ansible 2.0 or higher.

Role Variables
--------------

ansible_docker_user.
If it is defined, then at the end of the install, the user will be added to the
"docker" group. 
If it isn't, it'll fail fast

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: foo
      roles:
         - { role: dieswaytoofast.ansible_docker_utils, ansible_docker_user: barbaz }

License
-------

BSD

Author Information
------------------

Mahesh Paolini-Subramanya (@dieswaytoofast)
