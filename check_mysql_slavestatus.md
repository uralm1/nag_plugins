link: [claudiokuenzler.com/monitoring-plugins/check_mysql_slavestatus.php]

```
check_mysql_slavestatus.sh -S /var/run/mysql/mysql.sock -u user -p pass -w 60 -c 120
check_mysql_slavestatus.sh -H 127.0.0.1 -u user -p pass -w 60 -c 120
```
