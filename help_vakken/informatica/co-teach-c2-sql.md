---
description: alle SQL functies nodig voor examen SQL
---

# co-teach c2 (SQL)



## standaard functies

|                Functies                |
| :------------------------------------: |
|        STRFTIME('%x', klomnaam)        |
|                 DATE()                 |
|                 TIME()                 |
|             MIN(kolomnaam)             |
|             MAX(kolomnaam)             |
|             SUM(kolomnaam)             |
|             AVG(kolomnaam)             |
|                COUNT(\*)               |
|           DISTINCT(kolomnaam)          |
|            UPPER(kolomnaam)            |
|            LOWER(kolomnaam)            |
| SUBSTR(kolomnaam, startwaarde, lengte) |
|            LENGTH(kolomnaam)           |
|          CAST(... AS Integer)          |

### STRFTIME()

```sql
STRFTIME('%x', klomnaam) //verandert de datum syntax naar dagen, maanden, seconden, ect
```

in Het voorbeeld van deze functie woord '%x' gebruikt als placeholde

| %x vervangers | functie                      |
| :-----------: | ---------------------------- |
|       %d      | de dag(01-31)                |
|       %m      | De maand(01-12)              |
|       %Y      | Het jaar                     |
|       %S      | Aantal seconde(0-60)         |
|       %M      | Het aantal minuten(0-60)     |
|       %H      | op vragen van het aantal uur |



### DATE()

```sql
DATE() // Gets current date. The parentheses stay empty
```

### TIME()

```sql
TIME() //Gets current time. The parentheses stay empty
```

### MIN(kolomnaam)

```sql
MIN(kolomnaam) //gets the minimum amount of a group ints in a table
```

### MAX(kolomnaam)

```sql
MAX(kolomnaam) // gets the maximum of a group of integers in a table
```

### SUM(kolomnaam)

```sql
SUM(kolomnaam) //gets the sum of all the integers in a table
```

### AVG(kolomnaam)

```sql
AVG(kolomnaam) // gets a average of all the integers in a table
```

### COUNT(\*)

```sql
COUNT(*) //returns an integer value of the total amount of rows in a table
```

### DISTINCT(kolomnaam)

```sql
DISTINCT(kolomnaam) //only returns unique value's 
```

### UPPER(Kolomnaam)

```sql
UPPER(kolomnaam) // make all chars in a table of strings uppercase
```

### LOWER(kolomnaam)

```sql
LOWER(kolomnaam) // does the opposite of upper so it makes everything 
                 // lower case
```

### SUBSTR(kolomnaam, startwaarde, lengte)

```sql
SELECT SUBSTR(naam, 1,3)
FROM bezorger

// this returns from every bezorger the first three letters of there name
```

### LENGTH(kolomnaam)

```sql
LENGTH(kolomnaam) // returns a integer of the length of a string
```

### CAST(... AS Interger)

```sql
CAST(... AS Interger)// turns number stored as string into a integer type
```
