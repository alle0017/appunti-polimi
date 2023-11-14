## DEF coordinate polari: 
le coordinate polari del punto <u>x</u> = (x0, x1...xn) in R<sup>2</sup> \ {0, 0} è la coppia (&theta;,&rho;) dove &rho; è la lunghezza di <u>x</u> (||x||) e &theta; è l'angolo formato dal vettore <u>x</u> con l'asse delle ascisse.
x = &rho;cos(&theta;) y = &rho;sen(&theta;).

## DEF limite infinito:
sia f: R<sup>n</sup> -> R, si dice che il limite di f per ||x||->&infin; è +-&infin; se &forall;k>0 &exist;>R>0 t.c. |f(<u>x</u>)| > k &forall;<u>x</u>&isin;R<sup>n</sup> con ||<u>x</u>||>R
# CONTINUIT&Aacute; PER FUNZIONI IN PI&Uacute; VARIABILI

## DEF continuità:
sia <u>x</u><sub>0</sub> &isin;A&sub;R<sup>n</sup> con A aperto e f: A->R. Diciamo che f è continua in <u>x</u><sub>0</sub> se:
&exist; lim<sub><u>x</u>-><u>x</u><sub>0</sub></sub> f(<u>x</u>) = f(<u>x</u>)

# DERIVABILIT&Aacute;
## DEF derivata parziale:
sia A&sub;R<sup>n</sup> aperto, f: A->R e <u>x</u>=(x<sub>0</sub>,...x<sub>n</sub>)&isin;A. Diciamo che la derivata parziale di f rispetto a x<sub>i</sub> nel punto <u>x</u><sub>0</sub> è:<br>
&delta;f(<u>x</u>)/&delta;x<sub>i</sub> = lim<sub><u>x</u>-><u>x</u><sub>0</sub></sub> f(x<sub>0</sub>...x<sub>i</sub>+h,...x<sub>n</sub>)/h 
<br> solo se tale limite esiste finito. f si dice derivabile in <u>x</u><sub>0</sub> se tutte le derivate parziali in <u>x</u><sub>0</sub> esistono.

## DEF gradiente:
sia A&sub;R<sup>n</sup> aperto, f: A->R e <u>x</u>=(x<sub>0</sub>,...x<sub>n</sub>)&isin;A. se f è derivabile in <u>x</u><sub>0</sub>, allora diciamo che il gradiente di f in <u>x</u><sub>0</sub> è:
<br>&nabla;f(<u>x</u><sub>0</sub>) = (&delta;f/&delta;x<sub>0</sub>,...&delta;f/&delta;x<sub>n</sub>)
