- Normalizzare una base di dati significa rimuovere ridondanze
	- portare una base di dati in forma normale significa conferire la proprietà di base......
- Le ridondanze sono problematiche perhcè costringe ad una gestione delle ridondanze
- La procedura di normalizzazione permette di trasformare schemi non normalizzati in
- #+BEGIN_WARNING
  normalizzazione DIVERSO da forma normale
  #+END_WARNING
- la ridondanza porovoca problemi rispetto alla modifica e aggiornamento della base di dati
	- come anomalie di modifica/aggiornamento (costa tanto):
		- es(vedi slide): si vuole modificare il bilancio di un progetto, per farlo bisogna modificare l'importo per ogni impiegato di quel progetto
	- anomalie di cancellazione (si perdono dati):
		- es(vedi slide): nel momento della cancellazione di un progetto si perderà anche le informazioni dell'impiegato
	- anomalia di inserimento (si rischia di poter non lavorare con il DB per mancanza di info):
		- es(vedi slide): non è possibile aggiungere impiegati se non si sa il progetto di allocazione e la sua funzione
- ## Dipendenza funzionale
	- vincolo di integrità per il modello relazionale
	- descrive legami di tipo *funzionale* tra attributi di una relazione
	- #+BEGIN_TIP
	  serve a studiare in maniera sistematica i problemi legati a ridondanze e anomalie
	  #+END_TIP
	- nell'esempio non esiste legame funzionale tra impiegato e progetto
	- tra progetto e bilancio c'è legame