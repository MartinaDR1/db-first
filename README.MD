# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

- Id   | Bigint | Primary Key, Auto_increment, Not null, unique
- Marca   | Varchar (100) | not null
- Modello   | Varchar (100) | null
- KM   | Varchar (50) | null
- Anno di produzione   | YEAR | null
- Stato dell'auto   | Tinyint | default (0)
- Prezzo   | Decimal (10,2) | null 
- Descrizione   | Text | null
- Foto   | Varchar (255) | null
- Note   | Text | null
