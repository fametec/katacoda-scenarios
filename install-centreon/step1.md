# Disable SESELinux


`setenforce 0`{{execute}}

`sed -i s/SELINUX=enforcing/SELINUX=permissive/g /etc/selinux/config`{{execute}}



