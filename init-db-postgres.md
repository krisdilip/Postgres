### Create Database
1. Create "database" and "logs" directory
   
   mkdir D:\Project\pgsql\data
   mkdir D:\Project\pgsql\logs

2. Switch to bin directory
   
   cd D:\Project\pgsql\bin

3. Initialize the Database
   
   initdb -D D:/Project/pgsql/data

   This database system will be initialized with username "postgres".
   This user will own all the data files and must also own the server process.