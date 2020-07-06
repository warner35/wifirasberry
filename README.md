
## Installation

Clona el repositorio

```
git clone https://github.com/warner35/rasberrywifi.git
cd rasberrywifi
cp hosts.example hosts
otorga permisos de escritura

```

Edita la `interfaces` y el archivo `hosts`.

Deploy using [ansible](http://www.ansible.com) (install instructions for ansible are in [requirements](#requirements) below).

```
ansible-playbook playbook.yml -i hosts 
```

## Requirements

[Ansible](http://www.ansible.com/) is required. 



