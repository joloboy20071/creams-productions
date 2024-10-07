---
description: A simple mysql documentation of the avans software development notes
---

# Drop & Create table stament

***

## Drop Statement

***

### Example

***

#### Drop table

```sql
DROP Table TableName;
```

Removes a table from a database

***

#### Drop database

```sql
DROP DATABASE DatabaseName;
```

Deletes the whole database

***

## Create statement

***

### Create Database

```sql
CREATE DATABASE databasename;
```

***

### Create table

#### syntax

```sql
CREATE TABLE TableName(
    Columname0 DataType,
    Columname1 DataType,
    Columname3 DataType,
    ...
);
```

this creates a table with 3 colums \
\
Columname is how we want the collum to be called&#x20;

the datatype speseficy what we would like to be stored in a collums fields\
for available Datatype check [datatype page](datatypes-wip.md)

***

#### Example

```sql
CREATE TABLE peopleInfo(
    personID int,
    LastName varchar(255),
    firstName varchar(255),
    adress varchar(255)
    city varchar(255)
);
```

this creates a table called peopleinfo with five collums which can store information

***

### Create table from other table

***

#### syntax

```sql
CREATE TABLE NewTable as 
SELECT Colum1,Colum2,...
FROM ExistingTable
WHERE ...;
```

{% hint style="warning" %}
the WHERE statement is NOT needed when creating tables from other tables
{% endhint %}

***

#### Example

```sql
CREATE TABLE TestTable AS
SELECT CustomorNAME,ContactEmail
FROM Customors;
```

