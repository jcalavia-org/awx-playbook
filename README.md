# awx-playbook
Ansible AWX installation playbook

Configure an inventory file:

```
[all]
awx   ansible_host=[FQDN | IP]  ansible_user=[ssh_allowed_user]
```

Execute:

```shell
$> ansible-galaxy install -r roles/requirements.yml
$> ansible-playbook instal.yml -i inventory_file 
```