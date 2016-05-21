# Ansible-Trial-Tasks

Usage: 
1. Create key and security group for ec2
2. Change vars in aws role accordingly
3. Execute playbook to create and provison 2 instances

ansible-playbook -i ec2.py playbook.yml --extra-vars="count=2"
