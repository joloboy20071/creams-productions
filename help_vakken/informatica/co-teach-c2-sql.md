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
MIN(kolomnaam) //gets the minimum amount of a group ints in a tabel
```



###
