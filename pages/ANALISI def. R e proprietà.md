- Teorema: eisiste un insieme che si denota con R, dotato di:
  collapsed:: true
	- 1. 2 operazini: (+ e *)
	- 2. una relazione d'ordine
- che verifica le proprietà:
  collapsed:: true
	- algebriche
	  collapsed:: true
		- #+BEGIN_NOTE
		  inserisci slide propr alg di R
		  #+END_NOTE
		- tutte le propr di R valgono in Q
	- di ordinamento
	  collapsed:: true
		- riflessiva
		- antisimmetrica
		- transitiva
		- totale ordine: è sempre possibile stabilire se un elemento è minore di un altro
		  collapsed:: true
			- **NOTAZIONI**
				- <=
				- a,b∈R
					- a>=b <=> d<=a
					- a<b <=> a<=b *oppure* a≠b
					- a>b <=> a>=b *oppure* a≠b
	- di completezza
	  id:: 64059821-f939-4c7a-acd3-40189c7f1998
	  collapsed:: true
		- #+BEGIN_NOTE
		  vedi slides
		  #+END_NOTE
		- **INSIEMI SEPARATI**
			- dati A e B, due sottoinsiemi non vuoti di R. Si dice che A e B sono separati se
				- ∀a∈A, ∀b∈B a<=b
			- #+BEGIN_NOTE
			  in R esiste sempre un elemento di separazione e quindi completezza
			  #+END_NOTE
- **TEOREMA DI UNICITA'**
  collapsed:: true
	- l'insieme R è unico a meno di isomorfismi
		- #+BEGIN_WARNING
		  isomorfismi (?)
		  #+END_WARNING
	- se esistono due insiemi (A,+,*,<=) e (B,+,*,<=) che verificano le proprietà algebriche, di ordinamento e le prop di completezza allora esiste una fnzione bigettiva *f:A-->B* che cmmuta con le op e con l'ordinamento, cioè x,y€A
		- f(x+y) = f(x) + f(y)
		- f(x*y) = f(x) * f(y)
		- x<=y = f(x) <= f(y)
	-
- ## OSSERVAZIONI
  collapsed:: true
	- Distinzione tra Q ed R = ((64059821-f939-4c7a-acd3-40189c7f1998))
	- tutte le propr e di ord di R valgono anche in Q
	- le propr alg NON valgono in N e in Z
		- nessun elem di N ha un opposto
		- nessun elem diverso da 0 in Z ha un reciproco
	- in Q NON vale la propr di completezza: definiti A,B *contenuto* Q
		- id:: 6405a25c-7b84-49bd-8907-31acc6a6d92d
		  #+BEGIN_WARNING
		  formula mancante
		  #+END_WARNING7
- ## Radice n-esima
  collapsed:: true
	- Teorema: x>0 n€???????????
		- #+BEGIN_WARNING
		  NON SI CAPISCE UN CAZZO
		  #+END_WARNING
	- P'eq. t^{n}=x ha un'unica sol t>0
- ## Intervalli
  id:: 6405a435-b037-47e5-be93-3064488974e8
  collapsed:: true
	- sono insiemi che sulla retta corrispondono a segmenti o a semirette
		- **intervalli limitati**
		  collapsed:: true
			- siano a,b€R, a<b
			- [a,b]:={x€R|a<=x<=b}   -----|a+++++++b|--->
			- (a,b):={x€R|a<x<b}        -----a+++++++b--->
				- *NOTAZ ALTERNATIVA*: ]a,b[......
			- (a,b]:={x€R|a<x<=b}      ----a++++++++b|--->
				- *NOTAZ ALTERNATIVA*: ]a,b].......
			- [a,b):={x€R|a<=x<b}       ----|a+++++++++b--->
				- *NOTAZ ALTERNATIVA*: [a,b[.......
		- **intervalli illimiati**
		  collapsed:: true
			- a€R
				- [a, +∞) = {x€R|x>=a}     -----|a+++++++>
				- (a, +∞) = {x€R|x>a}        ----a+++++++++>
			- b€R
				- (-∞,b]:={x€R|x<=b}      ++++++b|--->
				- (-∞,b):={x€R|x<b}        ++++++b--->
	- **OSSERVAZIONE**:
		- R si può considerare intervallo: a volte si usa la notazione R=(-∞,+∞)
	- Proprietà caratteristica degli intervalli:
		- se *I* è uno delgi insiemi descritti sopra, allora vale la seguente propr
			- ∀x,y€*I*  [x,y]⊆*I*
			- x<y
- ## Estremi di un insieme numerico
  collapsed:: true
	- DEF: sia E *contenutouguale* R, E *diverso* *vuoto* e sia K€R, si dice che
		- k è un **maggiorante** di E se *perogni* x€E x<=k
		- k è **minorante** di E se *perogni* x€E k<=x
- def: E *contenutouguale* R, E *diverso* *vuoto*. E si dice
  collapsed:: true
	- **limitato superiormente**: se ammette un maggiorante (e quindi infiniti)
	- **limitato inferiormente**: se ammette un ????? (e quindi infiniti)
	- **limitato**: se ha un maggiorante e un ????
- **osservazione**
  collapsed:: true
	- E limitato <=> E limit sup oppure E limit inf
		- 1. E limitato
		  2. E limitato inf ma non sup
		  3. E limit sup ma non inf
		  4. N è lim inf ma non sup
		  5. Z,Q,R non limit sup ne inf
- **def**: E *contenutouguale*R, E *diverso* *vuoto*
	- si dice che M€R è il massimo di E se
		- M€E        (M è un elemento di E)
		- *perogni*x€E x<=M (M è un magg. di E)
	- si dice che m€R è il minimo di E se
		- m€E     (m è un elem di E)
		- *perogni*x€E m<=x (m è minorante di E)
	- si scrive M=maxE     m=minorE
- ESEMPI
	- E=[1,2]
		- 1€E, 1 è un minor di E --> 1=minor E
		- 2€E, 2 è un magg di E --> 2=max E
	- E={2,1/5}
		- 1/5=minE, 2 =maxE
- ## OSSERVAZIONE (importante)
	- se E_{+} *diverso* *vuoto* è sempre vero che esiste il minimo di E_{+}?
		- SI per la proprietà di completezza
	- se E_{-} *diverso* *vuoto* --> esiste max E_{-}
- TEOREMA DI ESISTENZA DELL'ESTREMO SUPERIORE
	- TEOREMA: di esistenza dell'estremo superiore
		- E *cointenutouguale* R, E *diverso* *vuoto*, E limit. superioremente. ALoora E_{+} def come sopra ha ??????
		- DOVE: E lim sup <=> E_{+} *diverso* *vuoto*
			- esiste almeno un magg
	- E ed E_{+} sono separati: *perogni* a€E, *perogni*b€E_{+} a<=b
- completezza di R: esiste c€R *perogni* a €E........