# Illarion-Ansible

![GitHub](https://img.shields.io/github/license/Illarion-eV/Illarion-Ansible)

Illarion Server Configuration

## Requirements

- Ansible
- Vagrant
- `ansible-galaxy collection install community.general`

## Local Server Configuration

- `vagrant up`
- `ansible-playbook illarion.yaml` or `./configure` as a shortcut
- To ssh into the VM and explore the result: `vagrant ssh`
- To reset the host key of the local VM when necessary: `./reset-known-hosts`
