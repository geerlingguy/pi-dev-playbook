# Raspberry Pi Development Ansible Playbook

This playbook installs and configures most of the software I use on my Mac for web and software development. Some things in macOS are slightly difficult to automate, so I still have some manual installation steps, but at least it's all documented here.

This is a work in progress, and is mostly a means for me to document my current Mac's setup. I'll be evolving this set of playbooks over time.

_See also_:

  - [Mac Development Ansible Playbook](https://github.com/geerlingguy/mac-dev-playbook)

## Installation

  1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).
  2. Clone this repository to your local drive.
  3. Run `$ ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  4. Run `ansible-playbook main.yml -c local` inside this directory.

Note: If you run the playbook from a different computer via SSH, remove the `-c local` from the command above.

## Overriding Defaults

Not everyone's development environment and preferred software configuration is the same.

You can override any of the defaults configured in `default.config.yml` by creating a `config.yml` file and setting the overrides in that file.

For example, TODO.

## Included Applications / Configuration (Default)

TODO.

## Ansible for DevOps

Check out [Ansible for DevOps](https://www.ansiblefordevops.com), which teaches you how to automate almost anything with Ansible.

## Author

[Jeff Geerling](https://www.jeffgeerling.com), 2020.
