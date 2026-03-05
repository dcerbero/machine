# ⚡ Software on my personal computer 

**Operating system:** macOS 15.x (Sequoia)

The main configuration files I use to install software on my personal computer

### 1 - Install ansible

On **macOS**:
```bash
# use Homebrew
brew install ansible
```
### 2 - Run playbook
For your personal computer configuration:
```bash
ansible-playbook -i inventoryPc.ini playbook.yaml
```

### 1.1 - Run playbook in virtualmachine for testing (ansible)
ansible-playbook -i inventoryLab.ini playbook.yaml