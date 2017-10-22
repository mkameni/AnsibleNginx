Role Name
=========


Installs firewalld.

Requirements
------------

None.

Role Variables
--------------

firewalld_service_accept_webserver:
  - { service: 'ssh', permanent: true }
  - { service: 'http', permanent: true }
  - { service: 'https', permanent: true }

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: adaware.firewalld }

License
-------

BSD, MIT

Author Information
------------------
