# MySQL Training - Köln
Training MySQL Windows

## SSL - Windows 

```
https://serverfault.com/questions/783861/enabling-ssl-in-mysql-when-using-windows-as-a-server-and-client

mysql -uroot -p --ssl-mode=REQUIRED 
mysql -uroot -p --ssl-mode=DISABLED
```
## Replikation - daten leeren
https://dev.mysql.com/doc/refman/8.0/en/data-directory-initialization.html

## show general instead of hex
select a.*, convert(a.argument using utf8) from general_log a;

##
 show global status like '%slow%';
