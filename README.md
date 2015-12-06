ansible-docker-compose
=========

Installs docker-compose on ubuntu.


Role Parameters
---------------

| Parameter name         | Description                                              | Default value             |
|------------------------|----------------------------------------------------------|---------------------------|
| docker_compose_version | Specifies the version of docker-compose to be installed  | [empty] => latest version |

Example Playbook
----------------

Example without parameters

    - hosts: servers
      roles:
         - ansible-docker-compose

Example without parameters

    - hosts: servers
      roles:
         - ansible-docker-compose
           docker_compose_version: 1.5.2