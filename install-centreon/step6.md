# Database management system

`mkdir -p  /etc/systemd/system/mariadb.service.d/`{{execute}}

`echo -ne "[Service]\nLimitNOFILE=32000\n" | tee /etc/systemd/system/mariadb.service.d/limits.conf`{{execute}}


`systemctl daemon-reload`{{execute}}

`systemctl restart mysql`{{execute}}


