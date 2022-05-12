Do a `vagrant up` in the directory to start provisioning of vms.
Do a `ansible-playbook playbook.yml` to run playbook.

Roles used:
-	https://github.com/avinetworks/ansible-role-docker for Docker installation with support for CentOS 7
- https://github.com/ansible/role-secure-docker-daemon (not available on ansible galaxy) to secure Docker daemon APIs
- https://github.com/atosatto/ansible-dockerswarm to configure Docker Swarm 
