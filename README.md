<table align="center"><tr><td align="center" width="9999">
<img src="icons/ansible.png" align="center" width="150" alt="MaaS icon">

# ServerManagement

</td></tr></table>

Simple home project employing Ansible automation framework for managing Debian distro Linux servers. This project contains few ansible playbooks e.g. playbooks
for installing software packages or playbooks for installing applications prerequisites like the Longhorn K8s distributed block storage.

## Requirements

Install requirements using ansible-galaxy with the following command:
```sh
ansible-galaxy install -r requirements.yml 
```

## Execution

You can simply run the playbooks with the following commands:
```sh
ansible-playbook addUsersAndPackages.yml
ansible-playbook longhornRequirements.yml
```
