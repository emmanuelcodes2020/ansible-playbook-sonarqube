#  Ansible playbook sonarqube






## Install Ansible roles 

```
ansible-galaxy install -r requirement.yml
ansible-galaxy install -r requirements.yml --roles-path roles

```



##  Run the ansible playbook 

```

ansible-playbook -i aws_ec2.yaml playbook.yml -b -u ec2-user --private-key=~/.ssh/sonarqube-key.pem

 ```