zabbix-dashboard-comments
===
expanding zabbix dashboard by adding quick what-to-do event comments for operation admins

In our company (and certainly not only in ours) several operation admins change during day at monitoring our services. We have introduced number of ways how to pass information between shifts. However many times during daily shift a new service is deployed to production and it needs to be monitored. This simple php frontend patch helps us submit "what-to-do" information to next admin in a quick way. Also a new trainee will know to react to issue which he'll see for the first time.

### usage
```
cd /zabbix/web/directry
patch -p1  < /path/to/zabbix_2.4.issue.comments.patch
```
