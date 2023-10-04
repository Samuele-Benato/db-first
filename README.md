## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

| COLONNA          | TIPO        | ATTRIBUTI            |
| ---------------- | ----------- | -------------------- |
| Chassis          | BIGINT      | PRIMARY KEY          |
| Brand            | VARCHAR(50) | NOTNUL               |
| Model            | VARCHAR(50) | NOTNULL              |
| Displacement     | SMALLINT    | UNSIGNED, NULL       |
| Production Year  | YEAR        | NOTNULL              |
| Price            | MEDIUMINT   | UNSIGNED, NOTNULL    |
| Number Of Owners | TINYINT     | UNSIGNED, DEFAULT(1) |
| Note             | TEXT        | NULL                 |
| Plate            | CHAR(7)     | NOTNULL              |
| Kilometres       | MEDIUMINT   | UNSIGNED, NOTNULL    |
| Fuel             | VARCHAR(25) | NOTNULL              |
| Condition        | TINYINT     | DEFAULT(1)           |
