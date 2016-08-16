# Change-root-password
Change root password on all the servers

This playbook will change the root/user password for all the servers listed in hosts file. 

It will prompt to enter the new root password which we want to use. 

Command to execute 

# ansible-playbook change-root-password.yml -k 
