#Docker course web api - Dometrain 


## spin up a sql server container :


```bash
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=Dometrain#123" -p 1433:1433 mcr.microsoft.com/mssql/server:2022-latest
```