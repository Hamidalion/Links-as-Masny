![Иллюстрация к проекту](https://github.com/Hamidalion/RepoPicture/blob/master/sql-logo.png)

# SQL#
### ⚙️ Preparing to DataBase
- [Dawnload SSMS](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) - Download SQL Server Management Studio
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) - Install SQL Server 2019 from Docker
```
***DOCKER***
docker pull mcr.microsoft.com/mssql/server              Create images Microsoft SQL Server
docker rmi $(docker images -f dangling=true -q)         Del unused images
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=Pass@Word1" -p 21143:1433 --name sql19-23t -v sqlvolume:/var/opt/mssql -d mcr.microsoft.com/mssql/server:2019-CU5-ubuntu-18.04
```

### 📚 Material to study
- [SqlDBM](https://app.sqldbm.com/SQLServer/Draft/) - Interactive SqlDBM
- [UT_VideoLesson](https://www.youtube.com/playlist?list=PL47zejIkBQvTJqvh9ZtNn01zwJ2lGXk-E) - SQL for beginners
- [SQL relationships](https://zametkinapolyah.ru/zametki-o-mysql/chast-3-2-vidy-svyazej-mezhdu-tablicami-v-baze-dannyx-svyazi-v-relyacionnyx-bazax-dannyx-otnosheniya-kortezhi-atributy.html) - Types of relationships between relational tables in a database.

- [One to many relationship](https://metanit.com/sharp/entityframework/3.7.php)


