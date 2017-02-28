gchiesa.portainer
=================

Deploy a portainer service in the docker swarm 

Requirements
------------

It requires ```gchiesa.iputils``` role for common utilities

Role Variables
--------------

The role uses the group ```swarm_managers``` to identify the group of manager nodes in a swarm cluster


Dependencies
------------

- gchiesa.iputils

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: swarm_cluster
      roles:
         - { role: gchiesa.portainer }

License
-------

BSD
