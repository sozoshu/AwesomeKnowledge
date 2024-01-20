# docker  
docker config an know how  

##For MSSQL docker image run:
ref1 https://docs.microsoft.com/en-us/sql/linux/quickstart-install-connect-docker?view=sql-server-ver15&pivots=cs1-bash
ref2 https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-setup-docker?view=sql-server-ver15
ref3 https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-configure-docker?view=sql-server-ver15
ref4 https://hub.docker.com/_/microsoft-mssql-server
```bash
docker pull mcr.microsoft.com/mssql/server:2019-latest
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=yourStrong(!)Password" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2019-latest
```
