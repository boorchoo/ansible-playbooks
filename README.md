# Ansible Playbooks
Ansible playbooks to simplify system administration and configuration.

## Fedora 37 Workstation Post Install
```
sudo dnf update --refresh
sudo dnf install ansible redhat-lsb-core python3-pip python3-jmespath python3-psutil
```
Restart the computer.
```
ansible-playbook -K playbooks/fedora-post-install.yaml
```

## Configure Apache HTTP Server

Update ```vhosts``` list in ```ansible-playbooks/playbooks/httpd-config.yaml``` with your virtual hosts.

```
ansible-playbook -K playbooks/httpd-config.yaml
```
