# INSERT INTO/ UPDATE / DELETE

***

## Insert values into table for all columns

***

### syntax

```sql
INSERT INTO TableName
VALUES(Value1, Value2, ... );
```

***

## Insert values into table for certain columns

***

### Syntax

```sql
INSERT INTO TableName(column1,column2,...)
VALUES(Value1,Value2,...);
```

***

## Insert values from other table&#x20;

***

### syntax

```sql
INSERT INTO TableName(Column1, column2, ...)
SELECT Column1, column2, ...
FROM OtherTable
WHERE ...;
```

{% hint style="danger" %}
BE AWARE!!!!! WHERE statement is not needed AND you can also use the insert table syntax of this [example ](https://app.gitbook.com/o/TATrlAYkem2Rg7WPIxd2/s/EZJpikjAR8f5jOqrUkvh/\~/changes/73/help\_vakken/notities/software-ontwikeling-avans/database-wip/insert-into#syntax)
{% endhint %}

***

## Update&#x20;

***

The update statement is used for changing values of existing table records

### Syntax

```sql
UPDATE TableName
SET Column1 = Value1, Column2 = Value2, ...
Where ...;
```

***

## Delete

***

The delete stament is used for deleting existing records from table

### Syntax

```sql
DELETE FROM TableName WHERE ...;
```
