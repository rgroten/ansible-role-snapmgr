ansibile-role-snapmgr
=========

Ansible role for deploying NetApp Snapshot Manager in a Docker container

Requirements
------------

Copy the NetApp SDK Python libraries into files/ directory  (NaElement.py, NaServer.py, NaErrno.py).
Download xml2json.min.js, ngProgress.min.js, and ngProgress.css into files/ directory

Role Variables
--------------

Configure the NetApp device(s) hostname/ip and credentials in defaults/main.yml
Set the config variables in template/config.ini.j2 (ie: enable LDAP)

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
