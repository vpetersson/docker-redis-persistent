# docker-redis-persistent

Redis docker container with persistent storage by default.

The only reason why I had to create this file was because Ansible's [Docker module](https://docs.ansible.com/ansible/docker_module.html) doesn't support `entrypoint` override until version 2.1.
