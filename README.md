Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name: auto_usate

- id: INT||BIGINT, UNIQUE, AUTO_INCREMENT, NOT NULL, PRIMARY KEY;
- modello: VARCHAR (50), NOT NULL, INDEX;
- brand: VARCHAR(50),
- descrizione: TEXT, NULL;
- anno: YEAR, NOT NULL, INDEX;
- month: MONTH, NULL;
- prezzo: NULL, DECIMAL(8,2);
- km: FLOAT(8,2), NULL ;
- carburante: VARCHAR(20), NOT NULL;
- potenza: VARCHAR(3), NULL;
- cilindrata: CHAR(4) || SMALLINT, NULL;
- cambio: VARCHAR(25), NULL;
- proprietari: CHAR(10), NOT NULL;
- colore: VARCHAR(50), NULL;
- TARGA: VARCHAR(7), NULL, UNIQUE;
- NUMERO DI CHIAVI: CHAR (1), NULL
  ˜˜- PAESE DI ORIGINE: VARCHAR (25), NULL, DEFAULT (IT);˜˜
- portiere: TYNINT, NULL;
- numero sedili: TYNINT, NULL;
- traction: VARCHAR (20), NULL;
- è disponibile? : TYNINT, DEFAULT(0);
- stato_macchina: VARCHAR(20), NULL ;
- note: TEXT, NULL;
- numero telaio: CHAR(17), NULL, UNIQUE;
