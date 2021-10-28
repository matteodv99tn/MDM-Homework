# MDM-Homework
## LaTeX crash course

Le cose che vi spiego qua le scrivo abbastanza velocemente, la cosa più comoda è comunque provare e sperimentare, e in caso vedere anche la parte di documento già scritta.

Il testo si scrive normalmente nell'editor, ma per scrivere in modalità matematica nel testo bisogna mettere le funzioni matematiche nel simbolo del dollaro del tipo `$ f_l(x) = 10 $`; in modalità matematica con `_` si può indicare il pedice, con `^` l'apice.
Per andare a capo riga all'interno di uno stesso paragrafo non bisogna andare a capo riga nel domumento .tex ma basta mettere due barrette `\\` così. Per creare invece un nuovo paragrafo (ossia andare a capo riga e aggiungere un rientro alla prima riga) è necessario lasciare nell'editor di testo almeno una riga vuota.

Per scrivere le equazioni centrate in una nuva riga è possibile sfruttare due metodi: se l'equazione non deve essere numerata allora bisogna creare un nuovo ambiente 


`\begin{equation}`


      la mia equazione
      
      
 `\end{equation}`
 
 Se non si vuole avere il numero progressivo a destra basta inserire l'equazione in questo modo `\[ equazione \]`.
