# ⚡ Software on my personal computer 
The main configuration files I use to install software on my personal computer

### 1 - Install ansible
```
sudo apt install ansible
```
### 1 - Run playbook 
sudo ansible-playbook -i inventoryPc.ini playbook.yaml

### 1.1 - Run playbook in virtualmachine for testing (ansible)
ansible-playbook -i inventoryLab.ini playbook.yaml

### Notes
- Configure rules ufw 
```bash
ufw enable
ufw default deny incoming
ufw default allow outgoing
```
pending configure ssh key 