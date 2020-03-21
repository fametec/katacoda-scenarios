# Add innodb_file_per_table=1 


```
cat <<EOF > /etc/my.cnf.d/99-centreon.ini

[mysqld]

innodb_file_per_table=1

EOF
```{{copy}}



