# SHERLOCKInfrastructure

Steps to build SHERLOCK infrastructure:

1. Run CloudFormation/SHERLOCK.template
2. Run commands in Ansible/ControlNodeInitialInstall.sh on Ansible host
3. From Ansible Host, run Docker playbook
4. From Ansible Host, run Jenkins playbook
5. From Ansible Host, run SHERLOCK playbook
