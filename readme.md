# Ansible Playbook

- Setup ansible 
- Setup hosts ( on .ssh/config directory to access the servers password less )
- Add playbooks with your commands
- Run **`ansible-playbook`**
- Command for playbook: **`ansible-playbook ./playbooks/*.yml --user ubuntu -i ./inventory/hosts`**
- For using multilpe Hosts configure the host file on **`/etc/ansible/host`**

## Inventory Sample 
```
[target_instance]
1.2.3.4 ansible_user=test ansible_password=test ansible_port=55221
```