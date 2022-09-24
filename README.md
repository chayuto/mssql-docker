```
docker-compose up
docker-compose up -d
docker-compose down

docker exec -it sql1 mkdir /var/opt/mssql/backup

docker cp DB_NEW_SME.BAK sql1:/var/opt/mssql/backup

```

https://docs.docker.com/samples/aspnet-mssql-compose/

https://hub.docker.com/_/microsoft-mssql-server?tab=description

https://learn.microsoft.com/en-us/sql/linux/sql-server-linux-configure-environment-variables?view=sql-server-2017

https://learn.microsoft.com/en-us/sql/linux/tutorial-restore-backup-in-sql-server-container?view=sql-server-ver16



