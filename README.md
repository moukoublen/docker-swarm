# Docker Swarm
Create a docker swarm with ansible (and vagrant for vms).


## Vagrant

To create the vms

```bash
cd vagrant
vagrant up
# or
vagrant up--provider=virtualbox

# To destroy
vagrant destroy --force
```


## Ansible

```bash
cd ansible

./bin/install-ansible-roles
./bin/install-ansible-collections

./bin/ansible-playbook docker.yml
./bin/ansible-playbook swarm.yml
```
