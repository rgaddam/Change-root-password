# Change-root-password
Change root password on all the servers

This playbook will change the root/user password for all the servers listed in hosts file. 

It will prompt to enter the new root password which we want to use. 

Command to execute 

# ansible-playbook change-root-password.yml -k 


rgaddam@localhost# grub-crypt --sha-512
Password:
Retype password:
$6$7XJAdPmhNnt1gdxi$N61RXKj..9aTeA5pQX2Mmw/A06h1j4gQHLigucarglTEn99ERO0YP9Z74puDyYuh3Bg0
rgaddam@localhost# 

https://github.com/ansible/ansible/issues/15326
