# [Docs](../README.md) / [Unix](Index.md) / DenyPassworLogin

Последние попытки входа по SSH
```
lastb | tail
``` 


Запрет входа по паролю
```
nano /etc/ssh/sshd_config
```
```
PasswordAuthentication no
```
```
systemctl restart ssh
```
