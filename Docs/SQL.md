![Иллюстрация к проекту](https://github.com/Hamidalion/RepoPicture/blob/master/sql-logo.png)

# SQL# Usefull links 

- [Dawnload SSMS](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) - Download SQL Server Management Studio
- [Dawnload SSMS](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) - Install SQL Server 2019 from Docker
```
docker pull mcr.microsoft.com/mssql/server              Create images Microsoft SQL Server
docker rmi $(docker images -f dangling=true -q)         Del unused images
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=Pass@Word1" -p 21143:1433 --name sql19-23t -v sqlvolume:/var/opt/mssql -d mcr.microsoft.com/mssql/server:2019-CU5-ubuntu-18.04
```