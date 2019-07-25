Role Name
=========

{{ cookiecutter.role_name }}

Requirements
------------

- For RHEL, a Red Hat subscription or functional local repository.

Role Variables
--------------


Dependencies
------------

- For Red Hat, subscription-manager.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: {{ cookiecutter.role_name }}

License
-------

MIT

Author Information
------------------

- {{ cookiecutter.author_information }}
