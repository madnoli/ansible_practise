# Ansible Practise

## 1. Cretating the user in RedHat and Debian based system using the ansible in AWS Cloud

 Required to pass the below parameter: 
 
       a. password
       b. username
       
 This playbook will create the user id, set the password, add the user in sudo/wheel group based on system distribution. 
 
 Will edit the sshd_config file and restart the sshd service to make it accept user login with password. 
