# Ansible auto provision

## Install ansible if you do not have it in your machine:

```
sudo apt-add-repository -y ppa:ansible/ansible
sudo apt-get update
sudo apt-get install -y ansible
```

## Run the playbook

```
ansible-playbook --inventory 'localhost,' -u giang playbook.yml --connection=local
```
Here we will use `--connection=local` if we install in localhost 
