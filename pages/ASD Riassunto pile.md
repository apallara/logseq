- la struttura dati pila è caratterizzata dal meccanismo di accesso LIFO, contiene elementi di tipo omogeneo.
  E' possibile realizzare le pile utilizzando una rappresentazione sequenziale o una collegata.
  La rappresentazione sequenziale prevede l'uso di un array e di un puntatore alla testa della lista.
  Le operazioni di inserimento e cancellazione hanno costo O(1) mentre la lettura O(n). Lo svantaggio principale di questa realizzazione è l'uso dell'array che è caratterizzato dalla rigidità, inoltre è probabile che molto spazio sia sprecato o che si debba ricorrere a meccanismi di raddoppiamento e conseguente copia, in questo processo la complessità è O(n).
  La rappresentazione collegata prevede che ogni elemento abbia un puntatore al successivo elemento, l'ultimo ha un puntatore nullo infine vi è un puntatore alla testa. Il vantaggio di usare questa realizzazione è data dall'assenza di rigidità del vettore mente le operazioni di inserimento, lettura e cancellazione mantengono le stesse complessità
-
-
- [[ASD pile]]