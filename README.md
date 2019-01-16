# dotfiles

## install ansible

```
$ sudo apt-get install python python-pip
$ sudo pip install -U ansible
```

## usage

```
# deploy .screenrc locally
$ ansible-playbook playbooks/roles/screen/tasks/main.yml -i inventory.yml --extra-vars "env=local"
```