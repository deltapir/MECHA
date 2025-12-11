# MECHA

## Cosa è MECHA
MECHA è un software scritto in Python che mi aiuta nei calcoli quotidiani della mia professione da termotecnico. 

## Perchè ho creato MECHA
Ho voluto accentrare in un unico ambiente tutti i fogli di calcoli, tool online, schede varie salvate in giro nel computer o trovate su internet.

L'ho pensato come uno strumento da tenere aperto mentre si lavora sui software di disegno più noti (per una distribuzione idronica o per la redazione di un P&ID) o mentre si scrive una relazione tecnica. 

Vuole essere un unico ambiente dove trovare tutte le formule e la teoria necessaria per sopravvivere nel mondo della termotecnica.

È un software che nasce da esigenze molto concrete in quanto io stesso lo utilizzo nel quotidiano. Pertanto, molte scelte grafiche e di interfaccia sono state effettuate cercando di rendere l'applicazione quanto più ergonomica possibile.

Gli ambienti coperti da questo software sono: Fluidica, HVAC, Vapore e Condensa, Gas Compressi.

Il software è ancora in beta e in fase attiva di programmazione.

---

### Dati tecnici modificabili
L'applicazione si basa su librerie scritte in **JSON**. Queste sono ampiamente modificabili dall'utente sfruttando un editor di testo o direttamente il *tool* presente all'interno di **MECHA** che elimina la necessità di conoscere l'ortografia dei file **.JSON**. Le librerie, pertanto, possono essere editate, esportate, importate e condivise con gli altri utenti. 

In pratica ogni tecnico può costruirsi il proprio "set di lavoro" all'inizio e poi riutilizzarlo nei progetti successivi e condividere il set stesso con gli altri colleghi di lavoro.

### Teoria fisica e trasparenza dei calcoli

Da ingegnere, so benissimo la necessità morbosa di conoscere la fisica e la teoria alla base di ogni calcolo e formula (come anche i requisiti al contorno che la rendono valida).

L'obiettivo è che ogni applicativo presente in **MECHA** venga arricchito da teoria, esplicitando le formule usate e citando le fonti utilizzate (manuali di termodinamica, documenti tecnici e, dove ha senso, norme e standard).

In questo modo è possibile usare l'applicazione con più coscienza e non come una scatola nera che fa magie.

---

## I quattro moduli dell applicazione

MECHA è organizzato in quattro moduli principali.  

### 1. FLUIDICA

In questo modulo ci sono tutti gli applicativi che riguardano il mondo dei fluidi (in particolare l'acqua e le sue miscele con glicole e sue varianti). 

È possibile:

- dimensionare tubazioni (in funzione di portata, velocità, perdita di carico, potenza);
- calcolare le perdite di carico (distribuite e concentrate);
- calcolare kV di valvole di regolazione degli skid di controllo;
- effettaure computi metrici (per massa/lunghezza di tubazioni, per superficie di isolamento e finitura esterna);
- dimensionare organi di centrale (valvole di sicurezza, accumuli, vasi di espansione, collettori...)

### 2. HVAC

In questo modulo ci sono tutti gli applicativi che riguardano il mondo della ventilazione.

È possibile:

- dimensionare canali (rettangolari e circolari) in funzione di portata, velocità, perdita di carico;
- effettuare computi metrici (per massa/superficie di lamiera, superficie di isolamento e finitura esterna);

Sono in fase di sviluppo i seguenti applicativi:

- effettuare calcoli psicrometrici tramite diagramma di Mollier interattivo;
- dimensionare un'unità di trattamento aria e scrivere un suo datasheet da fornire al costruttore;
- redigere un dataroom propedeutico al dimensionamento dell'unità di trattamento aria;
- dimensionare le batterie di riscaldamento dell'aria;

### 3. Vapore e condensa *[modulo in fase di progettazione]*

In questo modulo ci sono tutti gli applicativi che riguardano il mondo del vapore e della condensa.

Sarà possibile: 

- dimensionare le tubazioni per il vapore e la condensa; 
- dimensionare il vapore di flash;
- dimensionare gli organi di linea;

### 4. Gas Compressi *[modulo in fase di progettazione]*

In questo modulo ci sono tutti gli applicativi che riguardano il mondo dei gas compressi.

Sarà possibile:

- dimensionare le tubazioni;
- dimensionare organi di linea;
- dimensionare condensa;
- dimensionare la FAD per la selezione dei compressori;

### 5. Ulteriori applicativi futuri

Essendo il programma in beta, i 4 moduli su riportati saranno arricchiti di ulteriori funzionalità. 
Tra queste posso già elencare:

- supporto multilingua (attualmente il software è in italiano ma la prossima lingua prioritaria sarà ovviamente l'inglese - ulteriori lingue seguiranno in funzione delle necessità);
- supporto per più unità di misura (attualmente l'applicazione usa il Sistema Internazionale); 
- aggiunta di funzionalità per l'esportazione di report in PDF o .RTF con personalizzazione da parte dei singoli studi tecnici (loghi aziendali, carta intestata, etc.); 

## Acquisto, prova gratuita e sottoscrizione

L'applicazione può essere scaricata gratuitamente in questa pagina di GitHub ma è necessaria una licenza per poter usarla.

Per l'acquisto delle licenze mi appoggio a **Lemon Squeezy**.  
Il flusso è piuttosto lineare: 

 1. Accedi allo store di Lemon Squeezy usando il link evidenziato;
 2. Scegli il modulo più adatto o il bundle per l'intera applicazione;
 3. Completi il pagamento;
 4. Ricevi una licenza al tuo indirizzo email.

Per poter acquistare più singoli moduli è necessario effettuare fare più acquisti separati e aggiungere le licenze generate nell'applicazione.

In via predefinita, una singola licenza può essere usata su un unico dispositivo alla volta. La singola licenza può essere inserita in un altro dispositivo ma il sistema disabiliterà automaticamente il primo dispositivo. 

All'interno dell'applicazione è presente una sezione dedicata alla **gestione delle licenze**. Da lì è possibile inserire la licenza (o le licenze), verificarne lo stato e controllare che tutto sia attivo e in regola.

**Link per l'acquisto della licenza:**
Acquista o attiva la licenza MECHA su Lemon Squeezy:
https://INSERISCI_LINK_STORE_LEMONSQUEEZY

Puoi provare l'applicazione gratuitamente per **7 giorni**. Durante la trial puoi utilizzare MECHA.

Alla fine del periodo di prova, viene effettuato il pagamento che dà inizio alla sottoscrizione mensile.  

Per licenze personsalizzate (più utenti per licenze contemporaneamente), scrivimi in privato.

---

## Download, aggiornamenti e feedback

Puoi scaricare **MECHA** dalla sezione *Releases* di questo repository, dove trovi anche le note di rilascio con le novità di ogni versione.

Se mentre lo utilizzi ti viene voglia di:

- segnalare un problema;
- proporre un nuovo tool;
- suggerire un miglioramento dell'interfaccia o dei flussi;

puoi aprire una *issue* qui su GitHub o scrivermi direttamente.

Il progetto cresce molto grazie all'uso reale e ai commenti di altri voi colleghi. Ogni feedback mi aiuta a capire meglio cosa funziona, cosa è superfluo e dove vale la pena investire tempo per rendere MECHA uno strumento piu utile e piacevole da usare nel lavoro quotidiano.

In ogni caso, mi raccomando: 

> Leave the world a little better than you found it. 
[Baden Powell - fondatore dello scautismo]
