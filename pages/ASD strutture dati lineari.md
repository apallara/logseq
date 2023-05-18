- ## Strutture dati lineari
	- strutture che si sviluppano in una sola dimensione e che sono considerati in sequenza
	- tra gli elementi deve esistere una relazione d'ordine
		- #+BEGIN_NOTE
		  non si deve confondere la relazione d'ordine intesa come ordine alfabetico e il modo di ordinare gli elementi all'interno della struttura
		      ESEMPIO: ordine alfabetico **diverso** da ordinamento nel vettore
		  #+END_NOTE
	- per distinguere le strutture si deve considerare:
		- modi di individuazione della posizione relativa alla sequenza (modi di accesso)
		- modi di operare nella posizione individuata
	- **Modi di accesso**
		- **diretto** (es. vettore)
			- corrispondenza 1:1 tra rappresentazione fisica e logica
		- per **scansione** (es. liste)
			- si accede ad un elemento passando per tutti i suoi elementi
		- agli **estremi** (es. code, pile)
			- si accede solo al primo e ultimo
	- **Operazioni**
		- ispezione: lettura dei valori
		- cambio di valore: aggiornamento di un valore
		- scrittura: inserimento di un componente
		- cancellazione: rimozione di un componente