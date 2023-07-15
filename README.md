# Typescript for beginners


# Introduzione 
Typescript è un superset di Javascript, il che significa che tutto ciò che è possibile fare in Javascript può essere replicato in Typescript.

Tuttavia, è importante contestualizzare questa affermazione poichè spesso alcune persone credono erroneamente che Typescript aggiunga nuove funzionalità a Javascript. In realtà, Typescript non introduce nuovi concetti come callback o arrow function avanzate. L'obiettivo principale di Typescript è consentire di scrivere codice Javascript in modo più preciso, riducendo così gli errori durante l'esecuzione del programma.

Uno dei modi in cui Typescript ci aiuta è durante la scrittura del codice in uno dei nostri editor preferiti, in quanto rileva gli errori a tempo di scrittura.

Quindi, è importante sottolineare che Typescript non introduce nuovi costrutti come loop, classi o moduli. Infatti, il codice scritto in Typescript viene alla fine compilato in normale Javascript.


# Alcune cose da sapere

- Typescript non reinventa Javascript, ci chiede semplicemente di scrivere codice Javascript con maggiore attenzione.

- Typescript si concentra principalmente sulla sicurezza dei tipi. Prendiamo l'esempio di seguito.

  
![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/1fb6cdad-467e-46df-92f9-23788849a621)

Javascript permette alcune stranezze nel nostro codice, questo accade perché manca un sistema di sicurezza dei tipi. In realtà, avrebbe dovuto segnalare immediatamente, durante la fase di scrittura, che non possiamo sommare una stringa con un numero. Typescript semplicemente ci permette di prevenire queste stranezze.


# Typescript non è quello che pensi

Prima di immergersi in Typescript, è importante avere una chiara comprensione di ciò che Typescript è o non è. Questo ci aiuterà a comprendere meglio Typescript. Molti pensano erroneamente che Typescript sia un nuovo linguaggio di programmazione, ma questa affermazione non è del tutto accurata al 100%. Esiste una sottile differenza nella comprensione di Typescript, quindi cerchiamo di ottenere una visione chiara iniziale.
# Cosa fa TypeScript

TypeScript svolge principalmente il controllo statico (Static Checking): analizza il tuo codice e ti aiuta a identificare potenziali errori senza nemmeno eseguire il codice, evitando così errori in fase di runtime. Questa è la principale funzionalità di TypeScript.

Non è solo TypeScript a offrire questa capacità di controllo statico. Linguaggi come Java e GoLang seguono una filosofia simile, in cui il controllo statico viene utilizzato per individuare errori prima dell'esecuzione effettiva del codice.
