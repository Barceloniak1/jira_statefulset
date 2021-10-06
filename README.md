```
# Jira_statefulset
```

Clustered Version of Jira by Atlassian

Jira Version 8.19.0 with Postgres 13.3

```
Useful log files in Jira
```

| Location| Description |
| --- | --- |
| `/opt/atlassian/jira/logs/catalina.20XX-XX-XX.log` | Tomcat application server stdout |
| `/opt/atlassian/jira/logs/atlassian-jira-gc.20XX-XX-XX.log` | Garbage collection log |
| `/opt/atlassian/jira/logs/access_log.20XX-XX-XX` | HTTP access log (tomcat) |

More here : https://confluence.atlassian.com/jirakb/useful-log-files-in-jira-1027120387.html

```
Crucial locations 
```

| Location| Description |
| --- | --- |
| `/opt/atlassian/jira/conf` | server.xml; logging.properties, catalina.properties etc.  |
| `/opt/atlassian/jira/bin` | setenev.sh, catalina.sh, user.sh, tcnative-1.dll |