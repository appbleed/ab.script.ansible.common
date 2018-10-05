# Ansible create EC2 from AMI ansible role.

### Authored by Shravan Jha

# Pre-requisite
  - You have existing vpc, subnet and security group created in AWS
  - You have a role created in AWS to provision resources

# Objective

  - Create EC2 instance from an existing AMI with an existing vpc, subnet and security group
  - Create new key pairs and save it
  - Update inventory host file
  - Check SSH connection state is started

