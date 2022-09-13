### Start Database
1. Switch to bin directory
   
   cd D:\Project\pgsql\bin

2. Start database
   
   pg_ctl.exe -D  "D:/Project/pgsql/data" -l D:/Projects/pgsql/logs/ start

   Database will be listening on IPv4 address "127.0.0.1", port 5432