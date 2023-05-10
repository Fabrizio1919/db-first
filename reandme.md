<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario. -->
#  Database Intro Concessionario 

## data types : 

- Strings: varchar(number), char(number), text, longtext
- numbers: tinyint, small/medium int, int, bigint
- decimals: float(i, d), double(i, d), decimal(i, d)
- dates: DATETIME, DATE, YEAR, TIME, TIMESTAMP

## attributes: 

- NULL/NOTNULL
- DEFAULT
- AUTO_INCREMENT
- UNIQUE

## Entity name : Concessionario auto usate


- id | BIGINT, NOTNULL, AUTO_INCREMENT, UNIQUE
- casa_automobilistica | VARCHAR(50), NOTNULL
- km_effettutati | MEDIUMINT, NOTNULL
- modello |  VARCHAR(50), NOTNULL
- cilindrata | 	SMALLINT, NULL
- cavalli | SMALLINT, NULL
- peso | SMALLINT, NULL
- note | TEXT, NULL
- prezzo_di_acquisto | FLOAT(10, 2), NOTNULL
- prezzo_di_vendita | FLOAT(10, 2), NOTNULL
- targa |  VARCHAR(7), NULL, UNIQUE
- immgine_auto |  VARCHAR(250), NULL
- anno | YEAR, NULL