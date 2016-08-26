
# Assignment-Telenor 3
change to hosts for Deployment


[laradock]
192.168.1.2 ansible_ssh_user=ubuntu ansible_ssh_private_key_file=<your-pem>.pem

[kubernete]
192.168.1.2 ansible_ssh_user=ubuntu ansible_ssh_private_key_file=<your-pem>.pem


ready to Docker Envitonmenton and Auto build Nginx in docker container on aws ec2 do the below:

ansible-playbook -i hosts Docker-env-install.yml
ansible-playbook -i hosts docker-build.yml



Setup and Configure kubernete with Docker on AWS ec2 do the below:

ansible-playbook -i hosts kubernete-install.yml






Md Shariful Islam
Mod: 01717805091
email: jonaxm@gmail.com
ln: https://bd.linkedin.com/in/sharif7
