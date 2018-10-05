# Ansible common roles which can be used enterprise wide.

### Authored by Shravan Jha

# Objective

  - Create common roles which can be used in any other Ansible project.

# Prerequisites

  - Ansible and git are installed and you know what it does
  - You have an active AWS account Id and Key with role
  - Understand YML file structure
  - Basics of Ansible script
  - Basics of python, bash and powershell

### File Structure

Read below section to understand the purpose of each file/folder in this repo:

| FileName/Folder | Purpose |
| ------ | ------ |
| roles/[rolename] | Stores ansible role tasks, default vars, handlers. See more at https://docs.ansible.com/ansible/2.5/user_guide/playbooks_reuse_roles.html  |