# ansible-mongodb
Ansible playbook for installing MongoDB Versions 3.6 to 5.0 or upgrading from any Version 3.6 to 5.0. 

## Usage
- For installation, simply uncomment the role(version) you wish to install and run the ansible-playbook
- For upgrading from a previous version, change the `mongo_version` in anible-mongo.yml and uncomment the mongo-upgrade rule.
