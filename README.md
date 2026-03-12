# Atlas_of_Exoplanets  
Progetto 1 – La conquista dello spazio  
Corso di Interaction Design


Il Concetto  
Il NASA Exoplanet Archive contiene oltre 6000 pianeti confermati, con dati su temperatura, dimensioni e distanza. Purtroppo, però, è uno strumento per ricercatori: tabelle, parametri tecnici, nessun contesto narrativo.
Con questo progetto vorrei trasformare quei dati in un'esperienza divulgativa e interattiva, in cui l'utente impara cosa sono gli esopianeti, come vengono scoperti, e può anche esplorare liberamente l'archivio filtrando per temperatura, dimensione, distanza e anno di scoperta. L'obiettivo è far capire visivamente quanti di quei 6.000 pianeti si trovano nella zona abitabile e quanti no.


Target  
pubblico generalista, persone curiose, appassionati di spazio.  


Lingua  
Inglese.


Obiettivi  
- Far capire cosa sono gli esopianeti e che ne esistono migliaia
- Spiegare come la NASA li trova
- Mostrare visivamente quanti sono e che caratteristiche hanno
- Far emergere da quella visualizzazione quanti sono abitabili e perché è raro
- Rispondere implicitamente alla domanda: perché si fa questa ricerca


I Dati  
Fonte: NASA Exoplanet Archive — archivio ufficiale NASA.  
Formato: CSV esportato direttamente dalla piattaforma.  
Parametri scelti:  
| Parametro | Descrizione | Uso nel progetto |
| :--- | :--- | :--- |
| `pl_name` | Nome del pianeta | Schede di dettaglio, sistemi celebri |
| `pl_rade` | Raggio in raggi terrestri | Dimensione visiva, confronto con la Terra |
| `pl_eqt` | Temperatura di equilibrio stimata (K) | Colore, filtri di abitabilità |
| `sy_dist` | Distanza in anni luce | Posizionamento nella mappa |
| `disc_year` | Anno di scoperta | Timeline 1992–2026 |
| `discoverymethod` | Metodo di scoperta | Sezione sui metodi di rilevamento |
