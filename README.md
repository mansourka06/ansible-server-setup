# ansible-server-setup
Setup a server configuration of User Accounts, SSH, and Firewall, and installtin DevOps tools using Ansible.


### Prerequisites
- Linux basic knowlege

### Usage
:information_souce: **Informations**

Here is same step for using this project.

* 1- clone the repository: git clone https://github.com/mansourka06/ansible-server-setup.git

* 2- specialise your install by setting your in varibales in the [host_vars file](./ansible/host_vars/all)

* 3- Choose the role your want to install form the [playbook](./ansible/playbook.yml)

* 4- Configure your target host in [inventory file](./ansible/hosts.ini)

* 5- run the playbook: **ansinble-playbook playbook.yml**


### Auhtor
- [Mansour KA](https://github.com/mansourka06)
