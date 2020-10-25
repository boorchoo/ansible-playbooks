# Ansible Playbooks
Ansible playbooks to simplify system administration and configuration.

## Fedora 33 Workstation Post Install

```
ansible-playbook -K playbooks/fedora-post-install.yaml
```

## Configure Apache HTTP Server

Update ```vhosts``` list in ```ansible-playbooks/playbooks/httpd-config.yaml``` with your virtual hosts.

```
ansible-playbook -K playbooks/httpd-config.yaml
```
