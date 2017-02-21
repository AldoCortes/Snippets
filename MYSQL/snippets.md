MYSQL
---

#### Delete all tables on by one

> SELECT 'DROP TABLE [' + SCHEMA_NAME(schema_id) + '].[' + name + '];' FROM sys.tables
