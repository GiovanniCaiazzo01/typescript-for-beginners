# 1 - Typescript for beginners


## 1.1 - Introduzione a Typescript 
Typescript è un superset di Javascript, il che significa che tutto ciò che è possibile fare in Javascript può essere replicato in Typescript.

Tuttavia, è importante contestualizzare questa affermazione poichè spesso alcune persone credono erroneamente che Typescript aggiunga nuove funzionalità a Javascript. In realtà, Typescript non introduce nuovi concetti come callback o arrow function avanzate. L'obiettivo principale di Typescript è consentire di scrivere codice Javascript in modo più preciso, riducendo così gli errori durante l'esecuzione del programma.

Uno dei modi in cui Typescript ci aiuta è durante la scrittura del codice in uno dei nostri editor preferiti, in quanto rileva gli errori a tempo di scrittura.

Quindi, è importante sottolineare che Typescript non introduce nuovi costrutti come loop, classi o moduli. Infatti, il codice scritto in Typescript viene alla fine compilato in normale Javascript.


## 1.2 - Alcune cose da sapere

- Typescript non reinventa Javascript, ci chiede semplicemente di scrivere codice Javascript con maggiore attenzione.

- Typescript si concentra principalmente sulla sicurezza dei tipi. Prendiamo l'esempio di seguito.

  
![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/1.2.png)

Javascript permette alcune stranezze nel nostro codice, questo accade perché manca un sistema di sicurezza dei tipi. In realtà, avrebbe dovuto segnalare immediatamente, durante la fase di scrittura, che non possiamo sommare una stringa con un numero. Typescript semplicemente ci permette di prevenire queste stranezze.

- Scriverai molte più linee di codice in TypeScript rispetto a JavaScript, m.

## 1.3 - Typescript non è quello che pensi

Prima di immergersi in Typescript, è importante avere una chiara comprensione di ciò che Typescript è o non è. Questo ci aiuterà a comprendere meglio Typescript. Molti pensano erroneamente che Typescript sia un nuovo linguaggio di programmazione, ma questa affermazione non è del tutto accurata al 100%. Esiste una sottile differenza nella comprensione di Typescript, quindi cerchiamo di ottenere una visione chiara iniziale.

Alcune persone pensano erroneamente che in TypeScript si scriva meno codice e che venga automaticamente generato il codice JavaScript. In realtà, succede esattamente il contrario. In TypeScript si scrive molto più codice rispetto a JavaScript. Ma, nonostante ciò, il tempo e lo sforzo impiegati per scrivere in TypeScript sono ripagati dai benefici che offre.

## 1.4 - La sicurezza dei tipi in Typescript

TypeScript svolge principalmente il controllo statico (Static Checking): analizza il tuo codice e ti aiuta a identificare potenziali errori senza nemmeno eseguire il codice, evitando così errori in fase di runtime. Questa è la principale funzionalità di TypeScript.

Non è solo TypeScript a offrire questa capacità di controllo statico. Linguaggi come Java e GoLang seguono una filosofia simile, in cui il controllo statico viene utilizzato per individuare errori prima dell'esecuzione effettiva del codice.

## 1.5 - La scrittura del codice in Typescript

In TypeScript, scrivi il tuo codice utilizzando il formato ".ts" l'idea principale è che tu scriva il codice in TypeScript e poi questo viene trasformato in codice JavaScript.

Immagina che TypeScript sia come uno strumento di sviluppo che ti aiuta a scrivere un codice migliore. Ti permette di evitare più facilmente errori e rende il codice più facile da capire e gestire. È un po' come se TypeScript fosse una "scatola" che avvolge il codice JavaScript. Ma quando il tuo progetto viene eseguito o messo in produzione, il codice che effettivamente viene eseguito è sempre JavaScript puro al 100%. Quindi, TypeScript svolge un ruolo di supporto nel processo di sviluppo, ma alla fine il risultato finale è sempre un codice JavaScript comprensibile per il computer.

In breve, TypeScript ti aiuta a scrivere un codice migliore e più sicuro, ma è il linguaggio JavaScript che viene effettivamente eseguito dal computer quando utilizzi il tuo progetto.

# 2 - Come installare Typescript

## 2.1 - Piccola premessa
Ci sono due tipi di installazione di TypeScript: una globale e una specifica per il progetto. Inizieremo con l'installazione globale, che ti aiuterà a comprendere i concetti di base di TypeScript.

L'installazione globale ti permetterà di creare file di base e di capire le nuove funzionalità offerte da TypeScript. Tuttavia, quando utilizzi TypeScript in un progetto specifico, come ad esempio un progetto React o Angular, è necessario un file di configurazione TypeScript aggiuntivo. Questo file di configurazione ti permetterà di impostare le preferenze e le specifiche del progetto, come le impostazioni e le funzionalità che desideri utilizzare.

Inizieremo concentrandoci sull'installazione globale, in modo da poter creare dei file di base e comprendere le nuove funzionalità di TypeScript. Successivamente, passeremo alla sezione del progetto, dove vedremo come configurare le impostazioni di TypeScript in modo da poter produrre un codice migliore.

## 2.2 - Installazione 

Apriamo il nostro terminale ed eseguiamo il comando corrente: `sudo npm install -g typescript`

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/76209999-ec39-4329-b41e-ecd4ce069780)


Ora che TypeScript è disponibile nel nostro sistema, possiamo utilizzare un comando speciale chiamato TSC (TypeScript Compiler).

Per eseguire il comando TSC, possiamo aprire il terminale e digitare "TSC" seguito da altre opzioni. Ad esempio, possiamo utilizzare `"tsc -v"` per visualizzare la versione di TypeScript installata.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/a75e4aae-d174-4e37-8829-a5b81b6140d1)

Durante questo testo, ci concentreremo sulle fondamenta e i concetti principali di TypeScript, quindi qualsiasi versione di TypeScript funzionerà bene, non c'è motivo di preoccuparsi. Questi sono gli elementi fondamentali, le basi su cui si basa TypeScript. Sono concetti che non cambiano nel linguaggio stesso. Quindi, anche se stai utilizzando una versione precedente di TypeScript, non dovresti preoccuparti. I concetti fondamentali rimangono gli stessi.

# 3 - Hello Typescript

## 3.1 - Il nostro primo file `.ts`

Ora che abbiamo completato con successo l'installazione di TypeScript sul nostro sistema, possiamo finalmente creare il nostro primo file TypeScript. Per farlo, creiamo una nuova cartella nel nostro progetto, il nome non è importante.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/b8af730e-fe53-4a79-a0a3-94e54bf691b7)

All'interno di questa cartella, creiamo un nuovo file chiamato `hello_typescript.ts`. Ricorda che il nome del file può essere scelto a tua discrezione, ma è fondamentale assicurarsi che l'estensione sia `.ts` per indicare che si tratta di un file TypeScript.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/e4aeaf83-910e-447c-8373-c84dabf4ace2)

Ora vediamo come possiamo scrivere del codice e convertirlo in JavaScript. Iniziamo con un classico, il console.log. Possiamo utilizzare il console.log per scrivere il nostro nome sulla console. Questo è un codice normale di JavaScript e non ha nulla a che fare con TypeScript.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/b3af91e7-a999-492b-bf8f-e2808812a285)


Creiamo anche un paio di variabili. Per esempio, possiamo creare una variabile chiamata "user". Diamo un nome e un'età. Non mettiamo per ora l'email. Più avanti, vogliamo stampare il nome dell'utente utilizzando console.log. Ancora una volta, questo è JavaScript normale, niente di speciale con TypeScript.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/2ac47ead-9de8-4e32-8093-6018db361104)

## 3.2 - Da `.ts` a `.js`
Attenzione! Il codice che abbiamo scritto non può essere eseguito direttamente in TypeScript. Tuttavia, grazie all'installazione di TypeScript che abbiamo completato in precedenza, possiamo superare questa limitazione. Utilizzando il comando `tsc nome_del_tuo_file.ts`, possiamo convertire automaticamente il nostro codice TypeScript in un file JavaScript. In questo modo, otteniamo una versione del nostro codice che può essere eseguita correttamente.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/aabc1bbc-60ff-41ed-bcb5-efd6fe2f5a73)
![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/c0daa251-d48b-4c1b-b9b0-e4d881294746)
![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/e65a7355-2c89-44e0-a4d8-bd537496a235)

Questo è tutto ciò che fa TypeScript. Converte il tuo codice TypeScript in JavaScript, indipendentemente dal progetto che stai utilizzando. Questa è l'implementazione esatta di TypeScript. Ora, al momento, potresti notare che ci viene segnalato un errore.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/45c5c286-1868-48d8-9bdb-22469c3db6c9)

Studieremo in modo approfondito in seguito perché riceviamo questi dettagli sull'errore. Ad esempio, se proviamo a utilizzare `console.log` per stampare "user.email", ma "email" non è una chiave presente, TypeScript ci segnalerà immediatamente un errore già durante la fase di scrittura del codice. Questo ci aiuta a individuare e correggere gli errori in anticipo, rendendo il nostro codice più robusto e affidabile.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/08a4771c-a971-45bb-926e-e400dbb15319)

L'unico vantaggio che otteniamo è che TypeScript ci protegge da alcuni errori che potremmo commettere se scrivessimo solo codice JavaScript. Tuttavia, è importante sottolineare che TypeScript è solo uno strumento di sviluppo, un "avvolgimento" intorno a JavaScript per semplificarci la vita e renderla più sicura. Non c'è nulla che ci impedisca di eseguire il codice nonostante gli errori segnalati. Se eseguiamo il comando, vedremo che il codice funziona ancora, ma TypeScript ci avviserà dell'errore. Questo ci permette di correggere e migliorare il nostro codice durante 
la fase di scrittura.

![image](https://github.com/GiovanniCaiazzo01/typescript-for-beginners/assets/75174054/89b4b8f9-5bab-4052-82f1-ea4b7678a3a0)






