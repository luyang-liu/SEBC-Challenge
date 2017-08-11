* A command and output that shows the hostname of your database server :  

[root@ip-172-31-11-190 etc]# yum list|grep mysql|grep server
mysql-community-server.x86_64                5.5.57-2.el6                @mysql55-community
mysql-server.x86_64                          5.1.73-8.el6_8              base    


* A command and output that reports the database server version 
```
[root@ip-172-31-11-190 etc]# mysql -V
mysql  Ver 14.14 Distrib 5.5.57, for Linux (x86_64) using readline 5.1
```
* A command and output that lists all the databases in the server
```
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| hive               |
| hue                |
| mysql              |
| oozie              |
| performance_schema |
| rman               |
| scm                |
+--------------------+
8 rows in set (0.00 sec)

```
