# Full-stack-developer final project

# IP and SSH-PORT:
ip: 18.216.135.201
ssh port: 2200

# The URL to your hosted web application:
ec2-18-216-135-201.us-east-2.compute.amazonaws.com

# A summary of software installed:
- python3
- apache2 
- wsgi
- postgresql
- sqlalchemy

# configuration changes made:
- enabling ufw (Firewall) and allowing ports: 22, 2200, 80, 123
- creating user "grader" and making it sudoer
- generating an access key
- adding the file .ssh/authorized_keys to the "grader" user and past the public key in it.
- changing the access permission for the folder ".ssh" to be 700 and the file "authorized_keys" to be 644

# During this project I have been to "stackoverflow.com" a lot to solve any appering issues
