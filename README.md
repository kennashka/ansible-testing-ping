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

## Configure hosts file and verify/edit hosts in main.yml if needed

1. Replace (12.345.678.90) with your target server ip/domain address in hosts file 
2. Add the file location to ssh pem key in hosts file (ex. ansible_ssh_private_key_file= directory/location/to/your/pem/key/file)
3. Verify/edit hosts in main.yml if needed



## Run
```bash
ansible-playbook -i ./hosts ./main.yml
```
