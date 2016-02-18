Role Name
=========

Ansible role for deploying NetApp Snapshot Manager in a Docker container

Requirements
------------

Copy the NetApp SDK Python libraries into files/ directory  (NaElement.py, NaServer.py, NaErrno.py)
Download xml2json.min.js, ngProgress.min.js, and ngProgress.css into files/ directory

Role Variables
--------------


Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-role-docker
         - ansible-role-snapmgr

License
-------

MIT

Author Information
------------------

Ryan Groten <rgroten@gmail.com>
