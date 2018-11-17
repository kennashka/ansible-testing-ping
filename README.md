# ansible-testing-ping
Masternode Ping Test


### Version

1.1.0

## Ansible Install for Ubuntu

```bash
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt-get install ansible

```
## Run
```bash
ansible-playbook -i ./hosts ./main.yml
```
