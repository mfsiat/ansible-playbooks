# Ansible Playbook

- Setup ansible 
- Setup hosts ( on .ssh/config directory to access the servers password less )
- Add playbooks with your commands
- Run **`ansible-playbook`**
- Command for playbook: **`ansible-playbook ./playbooks/*.yml --user ubuntu -i ./inventory/hosts`**
- For using multilpe Hosts configure the host file on **`/etc/ansible/host`**
