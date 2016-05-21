# Ansible-Trial-Tasks

Usage: 
Create key and security group for ec2, and change vars in aws role accordingly and execute playbook to create and provison 2 instances

ansible-playbook -i ec2.py playbook.yml --extra-vars="count=2"
