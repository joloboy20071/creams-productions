# Subquerys

***

A Subquery can be used to write and run querys with in other querys or be used as conditions

### Example

```sql
SELECT Colum1, Column2, ...
FROM TableName
WHERE EXISTS
           -- subquery start   
           (
             SELECT Colum1, Column2, ...
             FROM TableName2
             WHERE ...;
           )
           -- Subquery end
```
