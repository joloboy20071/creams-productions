# Alter(WIP)

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
