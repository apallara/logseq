- le code sono strutture dati lineari costituite da elementi di tipo omogeneo, la struttura è caratterizzata a un accesso di tipo FIFO.
  E' possibile realizzare una coda mediante rappresentazione con puntatori e con vettore circolare. 
  La rappresentazione con puntatori prevede che ogni elemento abbia un puntatore al successivo elemento, inoltre vi sono altri due puntatori, uno alla testa e uno alla coda. In questa rappresentazione la lettura ha costo O(n), mentre l'inserimento e cancellazione hanno costi O(1).
  La rappresentazione con vettore circolare prevede l'uso di un vettore, un puntatore al primo elemento della coda e uno all'ultimo. In questa maniera l'inserimento e cancellazione hanno complessità costante, ma la lettura avrà O(n).
-
-
-
-
- [[ASD code]]