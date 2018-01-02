# Skywire setup playbook

This playbook makes the process of setting up skywire easier.

This is a work in progress so might not work perfectly. 

## Installation

  1. [Install Ansible](http://docs.ansible.com/intro_installation.html).
  2. Clone this repository to your local drive.
  3. Run `$ ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  4. Configure the variables in default.config.yml. 
  4. Run `ansible-playbook playbook.yml -i hosts` inside this directory. 
  5. Visit http://localhost:8000 to check the manager.

> Note: This has only been tested on Ubuntu. Might not work on windows.
