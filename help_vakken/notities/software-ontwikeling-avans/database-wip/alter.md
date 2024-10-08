---
description: a description of sql alter Statement
---

# Alter

***

## ALTER TABLE ADD

***

### syntax

```sql
ALTER TABLE TableName
ADD NewCollumName DataType;
```

***

### Example

```sql
ALTER TABLE customer
ADD Email varchar(255);
```

adds a collum Email to table customer

***

## ALTER TABLE DROP COLLOM

***

### syntax

```sql
ALTER TABLE tableName
DROP COLUMN CollumnName;
```

removes a collumn from a table

***

### Example

```sql
ALTER TABLE customers 
DROP COLUMN email;
```

removes column from table&#x20;

***

## ALTER RENAME COLUMN

***

### syntax

```sql
ALTER TABLE TableName
RENAME COLUMN OldName TO NewName
```

***

## ALTER COLUMN Datatype

***

### syntax

```sql
ALTER TABLE TableName
ALTER COLUMN ColumnName DataType;
```

the datatype speseficy what we would like to be stored in a collums fields\
for available Datatype check [datatype page](datatypes-wip.md)
