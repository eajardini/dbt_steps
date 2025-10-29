# Postgres

## User
```sql
create user my_user password 'postdba';  
CREATE DATABASE my_database  
    WITH   
    OWNER = my_user  
    ENCODING = 'UTF8'      
    CONNECTION LIMIT = -1;  
ALTER DATABASE my_database SET datestyle TO 'SQL, DMY';  
```
