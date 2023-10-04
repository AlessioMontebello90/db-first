Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

BONUS: nomi colonne in inglese
Buon divertimento e a domani!

---

| COLONNA     | TIPO         | ATTRIBUTI                            |
| ----------- | ------------ | ------------------------------------ |
| id_auto     | bigint       | INCREMENT-PRIMATY KEY-AUTO_INCREMENT |
| img         | text         | NOTNULL                              |
| brand       | varchar(50)  | NOTNULL                              |
| model       | varchar(50)  | NOTNULL                              |
| manufacture | year         | NOTNULL                              |
| KM          | int-unisgned | NULL                                 |
| fuel        | char(5)      | NOTNULL                              |
| info        | text         | NULL                                 |
| price       | decimal(7,2) | NULL                                 |
