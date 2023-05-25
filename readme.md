# Ansible
Ansible is a popular tool for configuration management, application deployment, and IT task automation. It is used to orchestrate and manage computer systems, networks, and cloud computing infrastructures.

## What you need to know about Ansible
- Client-Server Architecture: Ansible follows a client-server architecture with a controller and managed nodes.
- Inventory: The inventory is a file that lists the remote machines on which you want to perform actions.
- Playbooks: Playbooks are YAML files that describe the tasks to be executed on the managed nodes.
- Modules: Ansible uses modules to perform specific actions on the managed nodes.
- Tasks: Tasks are actions to be performed on the managed nodes and are associated with modules.
- Ad-hoc Commands: Ansible allows you to run one-off commands without creating a playbook.

## Preparing to use Ansible
First, you need to install it on Linux.

Then, run the following commands:

sudo apt update
sudo apt upgrade

Finally, install Ansible using the following commands:

sudo apt install ansible