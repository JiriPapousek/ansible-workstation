# ansible-workstation

Ansible playbook for my Ubuntu workstation.

## Usage
After installing Ubuntu OS execute the following lines in terminal:

```
sudo apt install git
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

For applying this playbook, execute this command:

```
sudo ansible-pull -U https://github.com/JiriPapousek/ansible-workstation.git
```
