Role Name
=========

Ansible Role: WordPress

This role installs and configures WordPress on a target server. It assumes that Apache and MySQL are already installed on the target system.

Requirements
------------
This role requires Ansible 2.9 or later, and has been tested on Ubuntu 18.04 and CentOS 7.

Role Variables
--------------
The following variables can be customized when using this role:

- `wordpress_db_name`: The name of the WordPress database to be created.
- `wordpress_db_user`: The username for the WordPress database.
- `wordpress_db_password`: The password for the WordPress database.
- `wordpress_url`: The URL for the WordPress site.


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
