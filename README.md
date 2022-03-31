# Ansible Practise

## 1. Cretating the user in RedHat and Debian based system using the ansible in AWS Cloud

 Required to pass the below parameter: 
 
       a. password
       b. username
       
 This playbook will create the user id, set the password, add the user in sudo/wheel group based on system distribution. 
 
 Will edit the sshd_config file and restart the sshd service to make it accept user login with password. 

## 2. Prerequisite for Oralce installation
  
 This playbook will do following tasks
 
       a. First it will create the oinstall and dba group
       b. Create the oracle user, set password as "root", add in secondary group wheel and dba
       c. Make primary group as oinstall group
       e. Install the all required packages
       f. Make all necessary kernel parameter changes. 
