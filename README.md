## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

| COLONNA          | TIPO        | ATTRIBUTI            |
| ---------------- | ----------- | -------------------- |
| chassis          | BIGINT      | PRIMARY KEY          |
| brand            | VARCHAR(50) | NOTNUL               |
| model            | VARCHAR(50) | NOTNULL              |
| displacement     | SMALLINT    | UNSIGNED, NULL       |
| production_year  | YEAR        | NOTNULL              |
| price            | MEDIUMINT   | UNSIGNED, NOTNULL    |
| number_of_owners | TINYINT     | UNSIGNED, DEFAULT(1) |
| note             | TEXT        | NULL                 |
| plate            | CHAR(7)     | NOTNULL              |
| kilometres       | MEDIUMINT   | UNSIGNED, NOTNULL    |
| fuel             | CHAR(2)     | NOTNULL              |
| condition        | TINYINT     | DEFAULT(1)           |
