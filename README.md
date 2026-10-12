# UAS SO A11.2025.16178 - Kevin Adijaya

VM: srv-kevin16178 192.168.61.78 | Domain: kevin16178.local

Subdomain: admin.*, mail.*

Ports: 22,53,80,21,40000-40100,25,143

Restore: cp *.conf ke /etc/... + systemctl reload

Note: Apache dipakai ganti nginx.conf, db-schema.sql ganti my.cnf. Semua secret ***REDACTED***.

