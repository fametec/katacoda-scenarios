# Disable SESELinux


Change to root user: 

`su - `{{execute}}



`setenforce 0`{{execute}}

`sed -i s/SELINUX=enforcing/SELINUX=permissive/g /etc/selinux/config`{{execute}}


In this scenario the SELinx isn't instaled. 

