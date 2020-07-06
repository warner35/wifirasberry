
## Installation

Clone and setup the ansible script. 

```
git clone https://github.com/warner35/rasberrywifi.git
cd rasberrywifi
cp hosts.example hosts
cp interfaces.example interfaces
```

Edit the `interfaces` and `hosts` files.

Deploy using [ansible](http://www.ansible.com) (install instructions for ansible are in [requirements](#requirements) below).

```
ansible-playbook playbook.yml -i hosts --ask-pass --become -c paramiko
```

## Requirements

[Ansible](http://www.ansible.com/) is required. 



