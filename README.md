# Stimolazione elettrica controllato da segnali mioelettrici  
 - MeCFES – un neuroprotesi
### Co-design di un ausilio avvanzato
 (Per la parte OpenSource il progetto continuo con acronimo LM)
 l progetto MeCFES (Myoelectrically controlled functional electrical stimulation) ha come scopo principale la riabilitazione di pazienti affetti da disabilita motorie. Si rivolge verso le persone con danni alla sistema nervosa centrale come: ictus, lesioni spinali, sclerosi multipla o trauma cranico, etc.
# Indice del progetto (link technici)
## English
Collaborative design results
Four repositories with documentation of the device have been published:
LM_APP https://github.com/ThorsenRune/LM-Android

LM_HW https://github.com/ThorsenRune/LM-HW

LM_ElAp https://cad.onshape.com/documents/661382f7fa0e94bae04c481c/w/cea5bdd3a732ac9eed1e4dd4/e/99b5a64c64c716ef593bdf7d

LM_FW  https://github.com/ThorsenRune/LM_FW


## Italiano
(Ancora da tradurre)


# Descrizione
La ricerca si basa principalmente sulla stimolazione degli arti superiori, sebbene la tecnica potrebbe essere estesa anche agli arti inferiori, con metodologie simili.

E' stato dimostrato che soggetti con lesione spinale oppure ictus possano trarre qualche vantaggio utilizzando un neuroprotesi. Il MeCFES è un dispositivo elettronico innovativo che combina stimolazione elettrica con controllo mioelettrici per sostenere vari movimenti utilizzando l'energia fornita da batterie. Tale funge come un neuroprotesi. Principio MeCFESUtilizzando elettrodi superficiali posti sulla cute sopra i muscoli interessati è possible rinforzare i movimenti voluntarie. Appunto il fatto che si cerca di aumentare il contrazione con un controllo che rispecchia immediatamente quello che l'utente cerca di fare, (ansiche techniche di controllo chiuso come spesso utilizzati nei neuroprotesi) è ipotizzato vantaggioso per l'utente. 

Abbiamo dimostrato che in alcuni soggetti con tetraplegia si potrebbe aumentare la forza della presa notevolmente. Ci sono anche discrete evidenze che soggetti con lesioni cerebrale ottengono vantaggi nella riabilitazione utilizzando il sistema per la rieducazione della mano.
Abbiamo dimostrato che in alcuni soggetti con tetraplegia si potrebbe aumentare la forza della presa notevolmente (vedi filmati).

Ci sono anche discrete evidenze che soggetti con lesioni cerebrale ottengono vantaggi nella riabilitazione utilizzando il sistema per la rieducazione della mano.
Come Funziona
Il sistema utilizza elettrodi di superficie sia per la registrazione dei segnali volontarie sia per la stimolazione. La combinazione tra stimolazione (FES) e signali mioelettrici (EMG) pone alcuni sfide tecniche. La difficoltà principale al livello tecnologico è stato di essere in grado di registrare tali segnali, a sua volte molto debole, mentre si stimola lo stesso muscolo con un intensità milioni di volte più grande del segnale mioelettrico.

Un analogia potrebbe essere di immaginarsi di cantare a pieni polmoni mentre si ascolta il bisbiglio di un altro.

Risolvendo questo problema il risultato è che un muscolo debole innesca la stimolazione con risultato di un maggior contrazione. Di nuovo un analogia semplice sarebbe quello del microfono amplificatore e le casse, un sottovoce viene amplificato per raggiungere migliaia di orecchie. Nello stesso modo il MeCFES utilizza il segnale di alcuni fibre muscolare ancora sotto controllo del soggetto per attivare altri unità motorie, non più sotto controllo volontario con il risultato di riluttare maggior forza. La stimolazione segue l’aumento o diminuzione del contrazione volontario in tempo reale ottenendo l’effetto di un servosterzo. Questo particolare consente di ottenere un movimento o forza senza eccessiva fatica da parte del utente disabile. I parametri che intervengono nella regolazione del neuroprotesi possono essere configurabili tramite un PC al fine di ottenere il controllo ottimale della mano da parte del paziente.

Vantaggi funzionali e terapeutici
Nel riabilitazione neuromotoria di pazienti con ictus si sa che il coinvolgimento del soggetto sottoposto alla terapia è di grande importanza [task oriented movement therapy]. Il metodo MeCFES consente al terapista di cominciare a lavorare insieme al paziente con movimenti che siano molto debole. A volte tale debolezza rende la partecipazione attiva difficile perchè potrebbe sembrare impossibile di raggiunger l’obiettivo. Invece l’aumento del movimento introdotto dal MeCFES permette ad alcuni pazienti di iniziare dei esercizi funzionale. Così inescando un feedback positivo il soggetto si sente in correggiato a lavorare coscientemente non solo con l'attivazione ma anche il rilassamento muscololare.

Persone con mieolesione potrebbe invece ottenere un controllato incremento della forza esibito in modo di per esempio ottenere una presa più ferma dei oggetti nella vita quotidiana. Altra importate aspetto riguarda il problema della percezione del proprio movimento. Il MeCFES funge anche ome bio-feedback perchè la stimolazione coinvolge anche la propriocezione.

### Come si costruisce il neuroprotesi
Il sviluppo scientifico del progetto ha portato un serie di pubblicazioni che descrive i dettagli della sistema. Inanzitutto serve del hardware elettronico costruito apposito per erogare la stimolazione simultaneamente con la registrazione del EMG. L’algoritmo di controllo richiede un elaborazione digitale che potrebbe essere eseguito di tanti recenti microcontrollori. Lo sviluppo elettronico ha reso possibile di miniaturizzare il sistema al punto che le batteria che devono fornire l’energia diventano la parte più ingombrante, ma anche li il progresso tecnologico lavora per noi. L’ultima parte ancora da risolvere al meglio è come realizzare un sistema indossabile. Attualmente i prototipi MeCFES richiedono che gli elettrodi vengono piazzate manualmente e collegati con fili di media lunghezza al unità di controllo. Seppure risulta funzionale sarebbe auspicabile di facilitare l’applicazione nel modo che utente potrebbe ‘indossare’ il neuroprotesi in autonomia.

### Prospettive futuri
Un obiettivo attuale è di rendere il sistema disponibile per tutti coloro che desiredono a testare la tecnica e valutare se sarebbe un soluzione per aumentare la propria autonomia e ridurre la disabilità. Sembra che ci sia una tendenza di auto-aiuto e di maggior coinvolgimento nel ricerca di soluzioni per le proprie bisogni di superare le sfide della vita quotidiana. Insieme al movimento dei ‘tinkers’ e ‘makers’ le base tecnologiche sono pronto per sostenere un Neuroprotesi free and open source, ovvero rendere possibile la riabilitazione fai-da-te, ovviamente in collaborazione con clinici ed istituzioni competenti.  


# Ulteriori informazioni
##Articoli divulgativi:

[La scarica elettrica su misura per i tetraplegici](http://salute.ilgiornale.it/news/21776/-fondazione-gnocchi-dispositivo-don/1.html)

## Links to older sites

### Inglish
[Sourceforge: Myo-Electrically Controlled Functional Electrical muscle Stimulation. An utility for assisting the tetraplegic hand. A method of rehabilitation after stroke.](https://sourceforge.net/p/mecfes/wiki/Home/)

### Italiano
