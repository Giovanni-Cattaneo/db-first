Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle `auto` usate messe in vendita da un `concessionario`.

- ID | INDEX | INT or BIGINT | NOTNULL | UNIQUE | AI(auto increment)
- CATEGORY | VARCHAR(20) | NOTNULL
- MARCA | VARCHAR(15) | NOTNULL
- MODELLO | VARCHAR(30) | NOTNULL
- COLOR | VARCHAR(15) | NOTNULL
- Kilometraggio | MEDIUMINT | NOTNULL | DEFAULT(0)
- N. TELAIO | VARCHAR(20) | NULL | UNIQUE
- ANNO DI USCITA | YEAR | NOTNULL
- NEW_OR_USED | TINYINT | NOTNULL
- IMMAGINE | VARCHAR(100) | NULL | DEFAULT(https://lorempicsum.jpg)
- CONDIZIONI (SOLO SE USATA) | TEXT | NOTNULL | DEFAULT (nuova)
- N. precedenti proprietari (se usata) | TINYINT | NULL | DEFAULT(0)
- NOTE | TEXT | NULL

