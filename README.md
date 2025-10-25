Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name: auto_usate

- id: INT||BIGINT, UNIQUE, AUTO_INCREMENT, NOT NULL;
- modello: TEXT, NOT NULL;
- descrizione: TEXT, NOT NULL;
- anno: YEAR, NOT NULL;
- prezzo: CHAR(5), FLOAT(2,3), NOT NULL;
- km: CHAR(6), FLOAT(3,3), NOT NULL ;
- carburante: VARCHAR(10), NOT NULL;
- potenza: CHAR(15), NOT NULL;
- cambio: VARCHAR(25), NOT NULL;
- proprietari: CHAR(10), NOT NULL;
- colore: VARCHAR(10), NOT NULL;
- TARGA: CHAR(7), NOT NULL;
- NUMERO DI CHIAVI: CHAR (1), NULL
- PAESE DI ORIGINE: VARCHAR (25), NOT NULL, DEFAULT (IT);
- portiere: VARCHAR(5), NOT NULL;
- numero sedili: VARCHAR(5), NOT NULL;
