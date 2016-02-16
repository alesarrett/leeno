# LeenO - Manuale d'uso

Versione 3.13.xx

leeno.org

Copyright (c) 2014-2016 Giuseppe Vizziello

Copyright (c) 2001-2013 Bartolomeo Aimar

è garantito il permesso di copiare, distribuire e/o modificare questo documento seguendo i termini della Licenza per Documentazione Libera GNU, Versione 1.1 o ogni versione successiva pubblicata dalla Free Software Foundation; senza Sezioni Non Modificabili, nessun Testo Copertina, e senza Testi di Retro Copertina. Una copia della licenza è acclusa nella sezione intitolata "Licenza per Documentazione Libera GNU".

*a Bart, alla sua ironia...*

### Note legali - Licenza per Documentazione Libera GNU

LeenO è Copyright © 2014-2016 di Giuseppe Vizziello ed è coperto da Licenza LGPL [http://www.gnu.org/licenses/lgpl.html](http://www.gnu.org/licenses/lgpl.html), perciò se ne può fare un uso personale e professionale libero.

Questo documento è Copyright © 2014-2016 di Giuseppe Vizziello ed è in gran parte basato sulla documentazione scritta da Bartolomeo Aimar per Ultimus.

Puoi distribuire e/o modificare questo documento nei termini della Licenza GFDL [http://www.gnu.org/licenses/fdl-1.3.html](http://www.gnu.org/licenses/fdl-1.3.html); per una traduzione non ufficiale in italiano potete fare riferimento a [http://it.wikipedia.org/wiki/Wikipedia:Testo_della_GNU_Free_Documentation_License/traduzione](http://it.wikipedia.org/wiki/Wikipedia:Testo_della_GNU_Free_Documentation_License/traduzione).

LeenO è un fork derivato da Ultimus che fu ideato e scritto da Bartolomeo Aimar.

Tutti i marchi citati\ in questo documento sono dei legittimi proprietari.

### Scarico di Responsabilità e Avvertenze
Come era scritto nel manuale d'uso e ripiegamento di un paracadute:

"... non so cosa sia questo oggetto, nemmeno a cosa possa servire, ma nel caso ti venga in mente di usarlo come paracadute ti consiglio di seguire scrupolosamente le istruzioni contenute in questo manuale!"

Lo stesso vale per LeenO. Non mi assumo alcuna responsabilità in merito agli usi propri o impropri che vorrai fare dell'insieme di macro contenute nella libreria LeenO, come non sono responsabile della possibile perdita dei tuoi dati.

Qualsiasi applicativo a sorgente aperto richiede, in ogni caso, una minima dose di "Responsabilità Personale".

	**Attenzione**
	I computi realizzati con le precedenti versioni possono non essere compatibili con le versioni 3.xx di LeenO.

	**Attenzione**
	Il presente manuale è in costante revisione e aggiornamento. Per questo motivo può essere disallineato dalla versione del software che accompagna.

### Contatti

LeenO - leeno.org - supporto@leeno.org\
Computo metrico assistito su LibreOffice\
Giuseppe Vizziello\
gsm: 328/2009610\
fax: 178/2717065\
skype: giuserpe

### L staff

mrjive (Davide Pesenti) webmaster, giuSerpe (Giuseppe Vizziello) sviluppo.

### Stato di revisione

|Numero|Data|Descrizione|Nome|
|------|----|-----------|----|
|3.8.xx-rev.1.1|Novembre 2013|Aggiunto par. “Prezzari in più capitoli”|G. V.|
|3.9.xx-rev.1.2|Marzo 2014|||
|3.11.xx-rev.1.3|Maggio 2015|||
|3.12.0-rev.1.4|Novembre 2015|||
|3.13.xx-rev1.5|Febbraio 2016|||

### Crediti
Difficile citare e ringraziare tutti, perché ho usato ampiamente la tecnica del copia/incolla, perdendo spesso per strada gli autori del codice originale.

Ma, al di là del codice, ringrazio innanzi tutto Carla Alessandria, che ha creduto in Ultimus (e in me) quando tutti - ad ogni clang del PC – si mettevano a ridere dicendo “...ma perché non usate Primus?”

Poi viene Paolo Mantovani, profondo conoscitore di OpenOffice e dei suoi linguaggi di programmazione, che mi ha sostenuto tecnicamente e moralmente. Senza di lui non avrei portato a termine questo lavoro (anzi, non l'avrei nemmeno iniziato). A lui devo molto... spero non si risenta nel vedere il suo nome “a copertura” di codice spesso pasticciato.

Lido Bernardini ha messo insieme, di sua propria e autonoma mano, molte parti del codice di LeenO (quelle migliori). Gli dovrei una intera cassa di birra...

Un ringraziamento a tutta la lista dev@it.OpenOffice, che mi ha sopportato ed aiutato... in particolare ad Antonello Cerrato, Emanuele (emanuele54@interfree.it), Fabio Fiorentini, Marco Caresia, Michele Zarri,... (chi ho dimenticato?)

Mrjive (al secolo Davide Pesenti) ha messo a disposizione lo spazio sul suo server e, insieme a giuSerpe (Giuseppe Vizziello), sta brigando con script, grep, e altri ammennicoli per rendere disponibili in LeenO altri Prezzari regionali.

Ma in particolare voglio ringraziare Giuseppe Vizziello (noto come giuSerpe), lo zoccolo duro dello staff, che si è occupato (e spero continui a farlo) di testare Ultimus in condizioni estreme su computi reali (sempre da consegnare con urgenza)... e su Contabilità complicate. Di questo aiuto gli sono molto grato.

A Laurent Godard ho plagiato un po' di codice ed ho fatto tesoro dei suoi consigli.

Con Andrew PitonyaK, Michael Dannenhöfer e DannyB non ho avuto contatti diretti, ma ho attinto ad ampie mani dal loro materiale pubblicato in rete... un ringraziamento anche a loro, e a tutti quelli che ho dimenticato di citare!

_Bart Aimar_

**Nota**

Ho assunto l'impegno di mantenere vivo il progetto di LeenO (già Ultimus) a seguito della scomparsa di Bart, avvenuta il 28 settembre 2013, per espressa sua volontà, ma l'avrei fatto comunque. Bart, fino alla fine, mi ha trasmesso “l'urgenza” di lavorare per LeenO e con LeenO. Produrre qualcosa che sia davvero utile a molti dà soddisfazione, e questo ci rende vivi.
Oltre che associarmi ai suoi ringraziamenti, anche io sento il bisogno di ringraziare:
* Carmen e Marianna Aimar che mi hanno accolto come se ci fossimo conosciuti da sempre e mi hanno permesso di accedere al PC di Bart come fosse stato il mio. Le ringrazio per non aver permesso che tutto ciò si fermasse e per avermi incoraggiato a proseguire la strada intrapresa dal loro caro.
* Davide Pesenti per il grosso supporto tecnico e logistico oltre che amichevole: è lui che si occupa del sito Internet e di incitarmi continuamente a proseguire.
* Albero Vallortigara per la sua preziosissima disponibilità a testare LeenO tempestivamente ad ogni nightly build e per suggerirmi pratiche soluzioni.
* Mariella, Ilaria e Michela per avermi lasciato lo spazio necessario.
* Chiunque, direttamente o indirettamente, riesca a partecipare al progetto LeenO.
* Bart (Bartolomeo Aimar) perché ha prodotto un gran lavoro e perché, fino all'ultimo, ha creduto nel suo progetto.
Lo ringrazio per avermi preparato a tutto questo.

_Giuseppe Vizziello_

### Premessa

Questo è un manuale d'uso, e non ho la pretesa che vi mettiate a leggerlo passo passo, ma con una ricerca (con i giusti criteri) all'interno del documento, e leggendo le sole parti che vi interessano, dovreste trovare le risposte ai vostri quesiti.

Se ci sono parti poco chiare, oppure obsolete (o del tutto criptiche) fatemelo sapere.

LeenO non è del tutto nuovo ma si tratta di un "porting" su OpenOffice di tabelle Excel assistite da macro che, in passato, abbiamo ampiamente utilizzato per la stesura di computi metrici.

Quando la cosa è cominciata c'era StarOffice 5.2 con il suo Basic incerto. Per questo ripiegai su Excel; poi, nel corso degli anni, sono state aggiunte man mano macro ed accrocchi vari, fino ad arrivare al vero salto qualitativo: la “traduzione” in StarBasic!

Su quelle tabelle assistite abbiamo comunque redatto molti computi metrici per opere di restauro complesse, per differenti amministrazioni e diverse enti finanziatori, e il "metodo" è stato ampiamente testato. Usandolo si sono evidenziate le doti di flessibilità delle tabelle di calcolo ad adattarsi a situazioni molto diverse, ma senza le tediose e ripetitive operazioni tipiche della fase di compilazione del computo.

La flessibilità di un computo metrico estimativo esclusivamente "tabellare" rappresenta infatti il suo punto di forza. Un Computo Metrico che possa in ogni momento essere modificato, riformattato, stampato usando anche soltanto i normali comandi di un qualsiasi programma in grado di editare quelle tabelle.

La traduzione delle macro in StarBasic ha comportato parecchi problemi, anche perché non sono un programmatore :-(

Il codice infatti è tutt'altro che elegante, ma conto sulla vostra collaborazione per migliorarlo.

Per chi vorrà addentrarsi in quel pantano prevedo dei forti mal di testa perché le macro a volte sono poco commentate... e man mano cerco di aggiungere commenti utili... spiegando, almeno a grandi linee, cosa fa quella macro e perché.

LeenO sembra funzionare egregiamente, ma siccome “ogni scarrafone è bello a mamma sua” vorrei conoscere le vostre impressioni!

Fatemi sapere.

	**Note**
	LeenO richiede una versione di LibreOffice pari o superiore alla 3.0.0. La versione corrente è testata su LibreOffice 4.3.7.
    _Da qualche versione in qua Apache OpenOffice ha perso colpi. La toolbar di LeenO non è visualizzabile e la tabella del COMPUTO non è riconosciuta. Problemi risolvibili, ma devo dare precedenza alla risoluzione di alcune procedure. Quindi, per usare LeenO installate LibreOffice._

	**Attenzione**
	Se non avete mai usato LibreOffice, vi consiglio, prima ancora di installare LeenO, di famigliarizzare con le sue tabelle di calcolo.

### Glossario e Convenzioni

L'uso di un font, rispetto ad un altro, individua nomi di elementi di diversa natura.

|Esempio di carattere tipografico|Significato|
|--------------------------------|-----------|
|S1.H318|Nomi di colonne o celle|
|menù|Nomi di menù a discesa/tendina o scorciatoia da tastiera|
|[VISTE]|Nome di menù a pulsante|
|COMPUTO|Nome dei foglio o di tabella|
|file.ods, 18|Nomi di file o valore di variabile|

In questo manuale d'uso:

* GUI sta per Graphic User Interface, ovvero l'interfaccia grafica standard di LibreOffice.
* Per codice si intende il testo scritto in linguaggio di programmazione LibreOffice Basic utilizzato per la creazione dei comandi di LeenO distribuiti sotto forma di “estensione” come unico file, preso dal sito leeno.org, con un nome del tipo LeenO-x.x.xx.oxt[^1].
* Per template di LeenO si intende il file OTS a cui LeenO fa riferimento per creare un nuovo lavoro che sia un computo metrico o un listino/prezzario.
* DCC o Documento di Computo o Contabilità Corrente: Si tratta del documento su cui stiamo lavorando. Vedi: DCC
* Per “codice” (scritto senza alcuna formattazione del testo) si intende una stringa alfanumerica che individua univocamente una voce di elenco prezzi completa di descrizione della lavorazione, unità di misura, prezzo unitario ed incidenze percentuali.
* Per “voce” intendo sempre il singolo record (in analogia con un record di database). Avremo pertanto:
    * “voci di Elenco prezzi”, sistemate su una sola riga
    * “voci di Analisi”, organizzate su più righe
    * “voci di Computo”, organizzate su più righe
    * e così via...
* Per “componente” si intende una delle righe di misurazione che compongo la voce di computo o libretto che costituiscono le diverse quantità di dettaglio. Oppure componenti di una voce di Analisi che sono le quantità ed i prezzi elementari delle lavorazioni che formano il nuovo prezzo.
* Lavorazione, Prezzo (o Prezzo Elementare): vengono così genericamente definite le Voci di Elenco prezzi.
* Per “header”si intende “Riga Intestazioni di pagina” Per “footer” si intende “piè di pagina”
* L'abbreviazione OOo sta per OpenOffice.org (suite per ufficio Open Source e multipiattaforma resa libera dalla SUN Microsystem, poi di Oracle, ora di Apache - AOO).
* L'abbreviazione LO sta per LibreOffice che tendiamo a preferire perché indipendente.
* Si citano indifferentemente LibreOffice o OpenOffice, in quanto l'estensione LeenO era utilizzabile sia con LibreOffice che con OpenOffice, sotto Windows, Mac OS X o GNU/Linux. Purtroppo, dalla versione 3.9.0, LeenO non è più testato con Apache OpenOffice e, per via del fisiologico divario che si va allargando dal fork di LibreOffice, la compatibilità con AOO si va perdendo.

[^1]: Talvolta il file da installare porta un nome del tipo LeenO-x.x.xx-timestamp.oxt in cui timestamp indica la data e l'ora del rilascio.

	**Attenzione**
	Proprio per problemi di incompatibilità crescente e perché il progetto Apache OpenOffice sembra del tutto abbandonato, eventuali ricorrenze nella documentazione di LeenO dei termini come Apache OpenOffice e OpenOffice.org costituiscono solo un retaggio.
	LeenO è testato solamente con LibreOffice.

* Le aree colorate in lilla indicano le celle dove si devono immettere i dati. (Figura 1)

**FIXME**
Figura 1

### Come si eseguono i comandi

**FIXME**
Figura 2

**FIXME**
Figura 3

Buona parte dei comandi di LeenO può essere impartita con modalità diverse: questo consente a ciascuno di scegliere la modalità che più gli corrisponde[^2]. Dal menù a tendina LeenO, dalla Toolbar o dai Pulsanti nei fogli/tabelle. (Figure 2 e 3)

Alle modalità sopra si aggiungono:

* Scorciatoie da tastiera (shortcuts); un elenco delle scorciatoie attive lo trovi nel file.ods (§ Scorciatoie da tastiera). (Maiusc+F1)
* Fogli del file.ods, corredati da tasti, usati come menù (ad esempio [menù PRINCIPALE (Alt+0)].

Quando parlo di click o di cliccare senza ulteriori indicazioni intendo sempre il pulsante sinistro del mouse.

[^2]: Per capire cosa intendo provate ad usare uno smartphone touchscreen, di quelli senza il manuale...:-)

#### Qualche specifica sulle Scorciatoie di tastiera:

* Ctrl è il tasto in basso a sinistra sulla tastiera
* Alt è quello a sinistra della barra spazio
* Invio (mi sembra eccessivo aggiungere altro...:-))
* Maiusc è il tasto della maiuscola.
* Per maggiore chiarezza la lettera viene sempre indicata con il carattere maiuscolo, ma si intende minuscola. (§ Scorciatoie da tastiera).

## CHE COSA E' LeenO

### Presentazione

LeenO è un applicativo per LibreOffice Calc, strutturato per la redazione di Computi Metrici e Contabilità tecnica di cantiere.

Un tempo (era il secolo scorso) i computi metrici venivano fatti compilando un modulo A3 prestampato, composto da righe e colonne. L'elenco prezzi era un analogo modulo in formato A4.

LeenO è esattamente la stessa cosa, ma su tabelle elettroniche collegate fra loro e che “fanno anche i conti”!

Partendo dal menù LeenO>Nuovo>Computo si ottiene un file che contiene diverse tabelle (dette anche sheet, tab, fogli, ecc.) sulle quali viene strutturato il computo metrico (con allegati quali: elenco prezzi, analisi di prezzo e quant'altro utile) e la contabilità lavori.

LeenO comprende anche una serie di utility che - a computo finito - serviranno a ripulire il documento da tutte le voci di Elenco Prezzi e di Analisi di Prezzo che non sono state usate nella tabella COMPUTO[^3].

In sintesi LeenO è un documento Calc, arricchito da diversi comandi di automazione, con delle tabelle predisposte su cui elaborare il computo metrico.

LeenO viene distribuito come unico file con nome LeenO-x.x.x.oxt. Un file.ods di esempio rimane sul sito Internet nella sezione download.

LeenO non lavora su database ma su tabelle Calc, comunque e in ogni caso, modificabili anche senza ricorrere ai sui comandi.

I lavori prodotti con LeenO rimangono liberi da LeenO che non è necessario installare per accedere ai dati.

LeenO, che deriva da LibreOffice tutte le sue caratteristiche, ne completa l’offerta, proponendo all’ufficio tecnico un sistema integrato per la gestione degli appalti, a partire dalla generazione della documentazione a base di gara, anche con l’ausilio di Writer, fino alla gestione dell’appalto in fase di esecuzione dei lavori ed alla conclusione dell’opera. Lavorando in ambiente Calc consente un'ampia manovrabilità e personalizzazione degli elaborati. 
Per computo metrico su DB ci sono altri progetti avviati:
* Fangus di Martello: http://mio.discoremoto.alice.it/martellofiles
* Preventares di Davide Vescovini: https://launchpad.net/preventares
* CompGos: http://xoomer.virgilio.it/compgos/

[^3]: In ogni caso una funzione (Ctrl TAB) consente di segnare a mano le voci dell'Elenco prezzi che si vogliono comunque mantenere. (NB In questo caso, prima di passare all'eliminazione, dovete ancora ripassare la macro generale di "segnatura" per taggare le dipendenti di quelle appena segnate manualmente.)

### Perché “LeenO”?

(Da un post su Google Plus: https://plus.google.com/+AlbertoVallortigara/posts/336uNTFg6hZ)

LeenO sta per Lino (abbreviativo di Bartolomeo).

Qualche tempo fa, sul canale IRC freenode.net/#libreoffice.it, si discuteva (Bart, mrjive ed io) cercando un nuovo nome per Ultimus. Siamo passati per 9vero (nòvero) che però si prestava a "non vero". Scherzando e ridendo abbiamo anche usato "Coso" :D.

Alla fine ci siamo soffermati su LeenO, con L ed O maiuscole per richiamare LibreOffice, perché ha assonanza con Linux e perché era giusto che portasse il nome di Bart, anche se lui non ne è mai stato convinto.

Quando Bart se n'è andato ci siamo convinti, soprattutto perché, alla fine, ha pubblicato ufficialmente la sua estensione con questo nome: http://extensions.libreoffice.org/extension-center/leeno-alias-ultimus

Ci saremo anche abituati, ma "Ultimus" non si può proprio sentire. Richiama troppo la ACCA :D.

Il nome Ultimus era stato scelto per gioco e non mi va che sia associato nemmeno per scherzo ad ACCA, che rispetto, ma con la quale Ultimus non ha niente a che vedere.

Ultimus è Libero, come lo è sempre stato Bart fino alla fine ed oltre.

Sto conoscendo Bart mentre studio e modifico il suo codice. Mi piace anche pensare che continui a guidarmi, visto che tra le macro trovo suggerimenti che sembrano rivolti a me direttamente. Non mi aveva mai invitato a lavorare sul codice e nemmeno credo l'abbia fatto con altri, ma nel suo codice continuo a trovare commenti del genere: "Adesso accontentiamo giuserpe che non la vuole al fondo..." oppure: "Sub Inserisci_Utili_giuserpe ' MODIFICATA PER GIUSERPE…"

Fino al momento in cui, cercando qualcosa di pronto che gestisse l'indice sul nuovo schema di prezzario ho trovato: "non so se é quello che cerchi ma io ci provo…".

Non riesco a leggere quella riga senza emozionarmi.

Mi piace pensare che Lino continui a guardarmi le spalle. Ecco, mi sono dilungato troppo. Non è da me :)

### Il Computo su formato OpenDocumentFile (ODF)

LibreOffice genera e gestisce file in formato OpenDocument (ODF) che è un formato standard aperto ISO/IEC 26300:2006. LeenO, essendo un add-on per LibreOffice, aderisce perfettamente allo stesso standard.

OpenDocument, come tale, garantisce interoperabilità senza barriere tecniche e legali anche tra sistemi operativi diversi, assicurando la scambio dei dati corretto e sicuro oltre che l’accesso agli stessi a lungo termine. Le sue specifiche tecniche sono di pubblico dominio, per cui favorisce la concorrenza impedendo che dette specifiche siano detenute da un singolo produttore di software.

### A chi è destinato

LeenO è destinato ad utenti di LibreOffice Calc che sanno come si fa un computo metrico e vogliono guadagnare velocità nella compilazione senza perdere margini di manovra e controllo dell'elaborato, preferendo, proprio per questo, l'utilizzo di fogli di calcolo.
Il marketing insegna che un programma di computo più rigido incontra maggiori consensi e aiuta l'operatore meno esperto, ma chi cerca un maggior controllo preferisce più libertà! Per questo, con l'aiuto e la collaborazione di molti amici, ho “assemblato” questo applicativo...:-)
Nonostante le premesse poco orientate al marketing si è comunque constatata un notevole facilità di approccio anche per utenti non particolarmente esperti. E' infatti molto usato per la stesura di computi finalizzati al calcolo dei “Costi di Costruzione” per le pratiche edilizie.
Il codice macro di LeenO è comunque aperto, nessuna protezione[^4] o password; l'utente ha il totale controllo della situazione.

[^4]: In realtà il documento è protetto da alcune manipolazioni accidentali, ma non ci sono password. Dal menù: LeenO>Ultilty>Sproteggi tutto il doc (Ctrl+Maiusc+K) si libera l'intero documento dalla protezione. (Alla riapertura del file.ods le protezioni verranno automaticamente ripristinate).

### Caratteristiche

* Possibilità di manipolazione dei documenti come una qualsivoglia tabella di calcolo, anche a work in progress, con l'ausilio dei soli comandi di Calc (i file prodotti con l'ausilio di LeenO rimangono consultabili ed anche gestibili senza installare LeenO – non dimentichiamo che stiamo trattando opendata).
* Centrale per i dati di Computo e di progetto (Anagrafica Generale) che verranno utilizzati da tutti i documenti in emissione, comprese le Copertine e i vari documenti di contabilità.
* Importazione voci di prezzario dal formato XML-SIX.
* Trasferimento all'Elenco prezzi di tutti i dati della voce individuata sul Listino (descrizione/i, prezzo, codice, incidenze manodopera e quota sicurezza).
* Per le voci di prezzo si possono usare sia i codici originali del Prezzario di riferimento che codici alternativi definiti dall'utente.
* Finestrella di ricerca del codice prezzo con completamento automatico delle specifiche della lavorazione. In alternativa selezione diretta delle voci dall'Elenco prezzi.
* Visualizzazioni preconfigurate delle colonne e visualizzazione in struttura dei dettagli in COMPUTO.
* Gestione analitica delle incidenze della manodopera a tutti i livelli (Elenco prezzi, Analisi, COMPUTO e CONTABILITA).
* Gestione analitica degli oneri di sicurezza a tutti i livelli (Elenco prezzi, Analisi, COMPUTO e CONTABILITA).
* Formazione di nuovi prezzi nel foglio di Analisi di prezzo sulla base del modello di riferimento pubblicato dall'AVCP(ora ANAC).
* Inserimento degli oneri di sicurezza afferenti l'Impresa[^5].
* Possibilità di spostare le intere voci di misurazionedell'ambito dell'elaborato.
* Possibilità di spostare e/o copiare range di righe dell'ambito dell'elaborato.
* Gli elaborati di base sono dinamicamente collegati ed interdipendenti.
* Possibilità di esportare - come nuovo documento consolidato - qualsiasi tabella (COMPUTO, Analisi di Prezzo etc.).
* Filtri automatici per selezionare categorie di voci (compilando celle opportune).
* Uso di filtri di ricerca.
* Visualizzazione “abbreviata” (troncata) delle descrizioni in Elenchi prezzi, in COMPUTO e nei prezzari.
* Possibilità di estrarre parti del computo (materiali, manodopera, categorie, etc) compilando celle opportune.
* Possibilità di riordinare le Analisi di prezzo secondo l'ordine alfabetico del codice-prezzo.
* Sezioni automatiche per capitoli e sottocapitoli e relativi subtotali.
* Possibilità di stralciare parti di COMPUTO generando un documento nuovo e autonomo.
* Possibilità di accodare un computo parziale, integrandolo nel documento principale. (lo strutturista, l'impiantista etc. dovranno ovviamente compilare la loro parte di computo su un analogo file.ods LeenO).
* Possibilità di trasferire da un COMPUTO all'altro una o più Analisi di prezzo.
* Possibilità - in qualsiasi momento - di “ripulire” il file.ods epurandolo di tutte le voci di Elenco Prezzi e di tutte le voci di Analisi che non sono state utilizzate in COMPUTO[^6].
* Compilazione di semplici preventivi attraverso la diretta immissione dei dati in COMPUTO (anziché utilizzare la formula di collegamento a Elenco Prezzi, si possono digitare direttamente descrizioni e prezzi nella stessa cella in COMPUTO).
* Possibilità di avere in Elenco Prezzi il sommario delle quantità inserite in COMPUTO e CONTABILITA con conseguente parallelo di raffronto.
* Contabilità a norma di regolamento LL.PP.
* Wizard per l'emissione degli atti contabili: libretto delle misure, registro di contabilità, sommario del registro, SAL e certificato di pagamento in un unico comando.
* Dotazione di copertine precompilate e collegate all'Anagrafica Generale.
* Output documenti finali in formato nativo ODS (standard ISO ODF[^7]) e in tutti i formati esportabili da Calc[^8].

[^5]: Questo dato è trattato come notizia e, perciò, non è coinvolto direttamente nella determinazione del prezzo di applicazione, ma viene annotato per poi poter essere trasferito in Elenco Prezzi.
[^6]: Una macro (Ctrl+O) aiuta comunque ad inserire un “segno” sulle voci che, anche se non usate, si vogliono comunque mantenere.
[^7]: Il formato ODF è uno standard aperto utilizzato da AOO, StarOffice, LibreOffice e pertanto utilizzabile da qualsiasi programma si voglia scrivere per quello scopo.
[^8]: L'esportazione (o il salvataggio) del computo in formato diverso da quello di ODS avrà come conseguenza la disattivazione irreversibile delle macro. Usatele solo per output finali!

### Requisiti

Sono indispensabili:

* Un computer sufficientemente veloce e con almeno 2 GB di RAM.
* Una versione _Still_ di LibreOffice [http://it.libreoffice.org](http://it.libreoffice.org).
E' noto che è considerata stabile, quindi più indicata per la produzione, la versione che porta come numero di minor release il 4 o superiore: ad es. 3.6.4, 4.2.5 e così via.
Dal sito di LibreOffice si legge: "_N.B. Il terzo numero del rilascio indica un aggiornamento del rilascio stesso (il numero varia da 0 a 7). Pertanto se desiderate una versione con nuove caratteristiche, ma meno testata, potete scaricare una versione con il terzo numero di rilascio più basso; se desiderate una versione con caratteristiche più datate, ma più testata e stabile scaricate invece una versione con il terzo numero più alto._"
* L'installazione del bridge Python-uno.
  * Sotto i sistemi Linux è necessario installare i pacchetti **python3-uno** e **libreoffice-script-provider-python**.
* L'estensione (add-on) _LeenO-XX.XX.XX.oxt_ da installare in LibreOffice; § installazione e aggiornamento.
* Tutto ciò che serve è all'indirizzo [http://leeno.org](http://leeno.org). Nel sito ci sono, oltre alla presentazione dell'estensione, il manuale, un archivio di vecchie versioni ed una raccolta di prezzari che si arricchisce sempre di più anche grazie agli utenti più collaborativi.

	Note
	Le xx.xx.xx che compaiono nel nome dell'estensione rappresentano i numeri di versione; sono tre gruppi di cifre.
	Non tutti i template sono compatibili con le versioni della libreria di macro, ma all'apertura di ogni documento LeenO effettua un controllo di compatibilità e vi informa degli eventuali problemi in merito, proponendo un aggiornamento automatico del file.

A titolo di documentazione riporto una schematizzazione con le relative compatibilità tra le versioni:
* major release: (1° gruppo di cifre - **xx**.xx.xx) totale incompatibilità con la versione precedente (travasi ed adattamenti sono molto difficoltosi). Il file-computo rimane sempre e comunque consultabile e gestibile con i comandi normali di Calc. Non dimenticare che stiamo trattando opendata.
* minor release: (2° gruppo di cifre - xx.**xx**.xx) implementazione di nuove funzionalità con probabile incompatibilità parziale del file che viene risolta tramite adattamento automatizzato alla versione corrente;
* sub version: (3° gruppo di cifre - xx.xx.**xx**) risoluzione di bug e/o regressioni.
Vedi anche Il pasticcio delle versioni (template vecchi con librerie recenti).

## INSTALLAZIONE E AGGIORNAMENTO

### Installazione

Oltre a LibreOffice l'unica cosa che dovete installare è _LeenO-xx.xx.xx.oxt_.

Prima di tutto è utile prendere dimestichezza con LibreOffice e con la sua interfaccia standard. Poi, prima di installare LeenO, aprite il computo di esempio che trovate sul sito, guardatelo e studiatelo un po'.

Osservate come sono strutturate le tabelle, le formule e i link che le collegano. Questo vi permetterà di familiarizzare con le tabelle costituendo una sorta di fase di "orientamento" alla quale potrà seguire l'installazione del pacchetto.

La libreria è distribuita come estensione di LibreOffice, ed ha un nome del tipo: _LeenO-xx.xx.xx.oxt_ (dove _xx.xx.xx_ è il numero di versione) scaricabile da [http://leeno.org](http://leeno.org).

E' sufficiente un doppio click sul file OXT per ritovarsi, in pochi attimi, il pacchetto installato (nemmeno il tempo per un caffè...).

Se ancora non lo avete fatto, è necessario abilitare l'esecuzione delle macro[^9]. § Come posso evitare ogni volta di abilitare le macro?

Anche con le macro abilitate, per rendere effettivi (e visibili) il menù e la toolbar, devi chiudere tutte le istanze di AOO (compreso il Quickstarter) e poi riaprire il file.ods di LeenO!

[^9]: Nelle ultime versioni di LO di default la sicurezza delle macro è impostata su Alta (o molto alta) che corrisponde a macro disattivate.

### Se qualcosa è andato storto

A volte succede che la libreria da aggiornare non venga sostituita in modo corretto e permanga (in tutto o in parte) nel profilo utente causando malfunzionamenti.

Se si hanno molte istanze di LibreOffice aperte può sfuggire qualche processo di troppo. Un modo certo per resettare LibreOffice è controllare, nel gestore dei processi del vostro sistema operativo, che non vi siano processi aperti con nome “soffice” (in Windows Ctrl+Maiusc+Esc).

In GNU/Linux, un brutale ed efficace pkill soffice (con i privilegi di root) dato in un terminale toglie ogni dubbio.

Nel caso abbiate ancora problemi con l'installazione del pacchetto OXT, vi rimane una soluzione radicale ma efficace: eliminare la parte corrotta dal vostro profilo utente.

Prima di tutto bisogna trovare il vostro profilo utente rilevabile anche da: Strumenti> Opzioni...>LibreOffice>Percorsi.

La maggior parte delle directory menzionate nella finestra di dialogo che compare fanno parte del profilo utente di LibreOffice.

Le cartelle sono nascoste, per cui assicuratevi che il vostro file manager sia impostato per mostrare i file e le directory nascoste. In ogni caso,
per le versioni precedenti a Windows Vista il percorso è:

> C:\\Documents and Settings\\<Vostro_nome_Utente>\\Dati Applicazioni\\LibreOffice\\4\\user\\

a partire da Vista il percorso è:

	C:\Users\<Vostro_nome_utente>\AppData\Roaming\LibreOffice\4\user\
Per chi usa GNU/Linux il percorso è:

	/home/<Vostro_nome_utente>/.LibreOffice/4 /user

Per quanti usano Mac il percorso è:

	/Users/<user name>/Library/Application Support/LibreOffice/4/user

Trovata la directory del vostro Profilo Utente accertatevi di aver chiuso TUTTE le istanze di LO (compreso l'eventuale quickstarter), controllando con un visualizzatore dei processi ancora in esecuzione.

Nel vostro profilo utente individuate la cartella “cache” (/.../4/user/uno_packages/cache/) e svuotatela eliminando tutti i files e le dir che vi sono contenute. Questo cancellerà tutte le installazioni delle estensioni. Una copia di backup dell'intero profilo non guasta e potrebbe tranquillizzarvi.

Riavviate LibreOffice e la cartella verrà ricreata. Reinstallate la vostra estensione (più le altre che avrete inevitabilmente perso).

### Tenere un archivio delle estensioni

Se volete essere certi di aprire un computo anche a distanza di tempo senza stress o sorprese, salvate da qualche parte la versione della libreria di LeenO che avete usato per crearlo[^10]. All'occorrenza installate la versione compatibile con il vostro file.ods.

Su leeno.org è presente un archivio corposo di tutte le versioni rilasciate negli anni; basta individuare quella che vi serve... 

Versioni differenti della stessa estensione non possono convivere. 

L'installazione di una versione, anche se antecedente a quella già presente nel sistema, elimina la precedente. Un doppio click sul file OXT provocherà la comparsa di questo avviso:

**FIXME**: inserire immagine

Comunque consiglio sempre di usare la versione più recente, eventualmente affrontando l'aggiornamento del vostro template.

[^10]: Non contate sulla la gestione online delle versioni obsolete di LeenO... E' una cosa che in realtà trascuro... non per pigrizia ma per problemi di comunicazione con il server. Nel caso scrivetemi che provvederò ad inviarvela via mail.

### Il pasticcio delle versioni (template vecchi e librerie recenti)

Come dicevo sopra spesso succede di dover rimettere mano ad un vecchio Computo, ma la libreria installata è più recente e viene restituito un messaggio che avverte dell'incompatibilità.

Per comprendere il problema è necessario prima prendere confidenza con il “sistema delle versioni” utilizzato... ovvero quello che mi viene da definire il “pasticcio dei numeri di versione”.

LeenO è composto da un "Template" (ovvero un file.ods Calc) più una serie di macro raccolte in una libreria.oxt (LeenO-X.X.XX.oxt). Questa libreria è specifica per una determinata famiglia di Template. Ovvero una certa versione di LeenO-X.X.XX.oxt opera correttamente solo su determinati Template.

LeenO, all'apertura di un template, ne verifica il livello di compatibilità e, nel caso ci siano problemi, vi informa.

La sigla di versione della libreria LeenO-X.X.XX.oxt è composta da tre gruppi di cifre (x.xx.xxx).

Un template di LeenO può avere nomi diversi, ma dal menù File>Proprietà potete leggere, nel campo dei commenti, per quale versione di libreria era stata creata (nei template molto vecchi non sempre aggiornavo quei dati...:-().

In ogni caso nella schermata del menù principale (Alt+0) vi sono delle indicazioni riassuntive (prelevate dalla tabella S1 del documento, celle H295 ed I295).

Confrontando i tre gruppi di cifre possiamo avere tre situazioni tipiche:
* Se il numero del primo gruppo non corrisponde il template è incompatibile (con alcune complicazioni il trasferimento dei dati (riversamento) rimane fattibile comunque[^11]).
* Se il numero del secondo gruppo non corrisponde la compatibilità e scarsa, ma l'aggiornamento del vostro documento è un'opzione percorribile (oppure si può usare la vecchia procedura di trasferimento dei dati (riversamento) in un file.ods aggiornato).
* Per la terza cifra non ci sono problemi: anche se diversa il file.ods è in genere compatibile.

Si tratta in genere di ottimizzazioni del codice o di correzioni di bug. Aggiornate sempre senza preoccuparvi.

Il template viene distribuito generalmente con un nome di questo tipo: Esempio_yyy_LeenO-3.1.xx, dove:
* yyy sono dei numeri qualsiasi (in genere progressivi) che io uso per distinguere un file da un altro.
* 3.1.xx è il gruppo di corrispondenza con la libreria del codice (vedi sopra).

Ma come dicevo sopra il “nome del documento” non ha importanza. Il documento può essere rinominato a piacere ed il codice andrà a leggere all'interno di esso individuando il grado di compatibilità.

Concludendo, i primi due gruppi dei numeri di versione di LeenO devono corrispondere ai due gruppi di numeri del template file.ods, ma, anche se questi corrispondono e dovete iniziare un nuovo computo, consiglio sempre di utilizzare la versione di template più aggiornata... perché anche questo è oggetto di frequenti aggiornamenti e migliorie.

Per la documentazione la situazione è molto più “fluida”, perché aggiorno quando posso.

TUTORIAL PER INIZIARE LeenO-3.x_xxxxxx.pdf

MANUALE D'USO-LeenO-3.X-xxxxxx.pdf

Il terzo gruppo di cifre, anche in questo caso rappresenta la versione di LeenO per la quale sono stati preparati, xxxxxx è la data del rilascio in formato yymmdd.

Fate riferimento alla versione più recente!

[^11]: La cosa prevede generalmente l'aggiunta e/o lo spostamento di alcune colonne nel computo sorgente per renderlo simile al Template di destinazione.

## ZOOM, VISTE E VISIBILITA'

Per usare comodamente LeenO occorre un'alta definizione video; questo per poter visualizzare un numero sufficiente di righe e di colonne. Ovvero sono giunto alla conclusione che, se la vista è buona e/o gli occhiali sono “giusti”, per vedere una porzione di tabella sufficientemente ampia sono necessarie definizioni minime di 1300x768.

Infatti sul mio portatile con una definizione come quella indicata sopra e con uno schermo di 15,5” riesco a lavorare decentemente. E' ovviamente preferibile un 21” (ma con definizione minima di 1920x1080 pixel).

Il template è impostato su rapporto 4:5 classico, ma se come me preferite usare schermi wide (in 16:9) è opportuno adattare le larghezze di alcune colonne, usualmente quelle che contengono testo su più righe[^12]. Ma questi sono solo consigli e potete fare come meglio preferite.

Un'altra variabile è quella dei caratteri installati sul vostro Sistema Operativo... ma, in ogni caso, la funzione “Sostituzione caratteri”[^13] di AOO può risolvere molti problemi al riguardo... (come ad esempio rendere più leggibili i pulsanti).

[^12]: Elenco Prezzi colonna B, Analisi Col B, COMPUTO col I (I come India), CONTABILITA col C … e così via.
[^13]: Menù Strumenti>Opzioni...>LibreOffice>Tipi di carattere... spunta su “applica tabella di sostituzione”.

### Zoom

Al caricamento del documento un automatismo sistema lo zoom in modo che la schermata “standard” riempia la finestra disponibile; (questo funziona soltanto se il documento era stato salvato con la finestra massimizzata[^14]).

In ogni caso il valore di zoom rilevato in quel momento viene registrato tra le Variabili generali e potrete riportare lo zoom a quel valore usando l'opzione:

menù LeenO>Zoom a Default (oppure dalla toolbar l'icona con la lente)

La default è impostata su 1, cioè lo zoom viene impostato per avere una buona visione con uno schermo medio e con scarsa definizione.

Con la variabile H292 impostata a 4 lo zoom sarà ottimizzato per uno schermo grande ed alta definizione. L'opzione 5 invece è per schermi wide.

In ogni caso potete impostare un valore di zoom nella cella H293, ma dopo aver settato a 2 la cella H292. Oppure disattivare del tutto l'automatismo impostando H292 a 3.

Nel caso preferiate avere uno zoom diverso per ciascuna tabella occorre modificare una impostazione di Calc:

menù Strumenti>Opzioni...>OpenOffice Calc>Vista>Zoom>Sincronizza fogli.

In tal caso l'automatismo di gestione dello zoom non darà più aggiustamenti uniformi!

Di lì in avanti potrete regolarlo a seconda delle necessità tenendo premuto Ctrl e agendo sulla rotella del mouse. (Sembra un consiglio superfluo... ma molti non conoscono questa opzione!).

C'è ancora una possibilità. Dopo aver selezionato le colonne che di intende visualizzare al meglio, da menù selezionate: Visualizza>Zoom...>Ottimale.

In LibreOffice c'è anche un cursore scorrevole (scrollbar) in basso a dx nella riga di status che consente l'aggiustamento dello zoom.

Poi, nel caso, esistono altre cose da fare per adattare le schermate di LeenO alle proprie esigenze.

Le variabili in gioco sono tante, ma qualche suggerimento non guasta. Potete agire su:

* Strumenti>Opzioni...>OpenOffice>Vista>interfaccia Utente>Scala
* Strumenti>Opzioni...>OpenOffice>Vista>interfaccia Utente>Dimensione e stile icona
* Strumenti>Opzioni...>OpenOffice>Caratteri>Applica Tabella di sostituzione
* Larghezza delle colonne (Quando i caratteri sono leggibili conviene operare sulla larghezza delle colonne...).
* Utilizzo di uno stile di testo del tipo Narrow.

	Attenzione:
    Sulle tabelle Elenco Prezzi, COMPUTO e CONTABILITA per guadagnare visibilità è possibile attivare una visione “corta” (troncata, abbreviata) delle descrizioni (si attiva/disattiva con F3 oppure con Ctr+Maiusc+L sulla specifica tabella).

Comunque è sempre magico lavorare di zoom usando la rotella del mouse e tenendo premuto Ctrl...

Per le operazioni di stampa è comodo attivare:

menù Opzioni...>OpenOffice Calc>Vista>Interruzioni di pagina.

In questo modo i bordi dell'area di stampa e i salti pagina sono visibili anche in vista Normale. In ogni caso la leggibilità delle varie tabelle va “giocata” anche con le opzioni:

* menù Finestra>Fissa
* menù finestra>Dividi

...secondo i gusti personali.

Se proprio volete cambiare o modificare le scritte nei pulsanti dovete farlo lavorandoli uno a uno in questo modo:

* disattivare prima la protezione del documento con Ctrl+Maiusc+K (o dal menù a tendina)
* menù LeenO>Modo Bozza on/off
* modificate i pulsanti a vostro piacimento...
* riattivate le macro con menù a tendina LeenO>Modo Bozza on/off

[^14]: In questo simpatico “giochetto” altre cose potrebbero andare storte... ad esempio le righe per le barre di menù in numero maggiore di tre... e in questi casi i menù di schermo potrebbero essere più grandi della schermata e qualcosa in basso non sarà visibile... In ogni caso, questo Zoom Automatico è controllabile e/o disattivabile dal sottomenù Variabili generali celle H292 e H293

### Viste

Il pulsante [VISTE] (o Maiusc+F10 o ancora dall'icona sulla toolbar) apre delle finestre di dialogo diverse a seconda del contesto[^15]. Da quella finestra di dialogo si possono organizzare diversi “scenari” nascondendo o mostrando colonne o gruppi di colonne o azionare delle vere e proprie macro.

Inoltre, dalle versioni più recenti, il dialogo [VISTE] è stato espanso trasformandolo in una sorta di menù contestuale alla tabella dove sono possibili anche una serie di 'Azioni' che in questo contesto ignorerei badando solo alle vere e proprie 'Viste' attivabili!

Provate a cliccare su qualche pulsante... spiegare mi sembra più complicato...

Molto utile è la visione “troncata” delle descrizioni (tipica dei programmi di computo sviluppati su DB[^16].

Si tratta solo di una impostazione forzata dell'altezza di quelle righe ma è (per lo scopo) efficace. L'impostazione dell'altezza di quella riga è modificabile nelle Variabili Generali alla cella H311.

Si attiva/disattiva da [Viste] o dalla toolbar.

Anche attivando la CONTABILITA ci ritroviamo con una finestra di dialogo diversa da quella che si vede durante la stesura del computo[^17].

Dalle versioni 3.6.xx il dialogo delle [Viste] è disponibile anche su Elenco prezzi e sulle Analisi di prezzo, sopratutto come menù contestuale per alcune azioni.

[^15]: Cioè diverse a seconda della tabella da cui viene azionato il comando
[^16]: La visualizzazione corta (o troncata) è disponibile su diverse tabelle e si agisce con F3 (oppure Ctrl+Maiusc+L, dalla toolbar e dal menù top).
[^17]: Si suppone che la contabilità venga “attivata” solo ad Appalto avvenuto.

**FIXME**:inserire immagine

### Strutture

E' possibile strutturare (raggruppare) gruppi di righe e colonne automaticamente usando le icone della toolbar o la scorciatoia Alt++ (oppure Ctrl+M).

Le situazioni sono diverse a seconda della Tabella su cui vengono attivate (l'immagine sotto è quella del COMPUTO); notate che non sono più visibili le “misure parziali”.

**FIXME**: inserire immagine

Per nascondere o rendere visibili i vari raggruppamenti usate i pulsanti in alto a sinistra. (Intendo i quadratini con 1 2 3 cerchiati in rosso in alto a sinistra).

Con Alt+- (Alt e segno di sottrazione) oppure Ctrl+Maiusc+M le strutture verranno eliminate ripristinando la situazione normale. Entrambe le operazioni possono essere fatte dal pulsante [Viste], se visibile.

	Note:
	Per utilizzare il livello 1 è necessario inserire delle intestazioni di capitolo.

La visibilità dei livelli di struttura può essere modificata attraverso le Variabili Generali (Vedi: come modificare il comportamento).

### Schermo intero

Questa non è una opzione di LeenO ma una possibilità offerta da  LibreOffice.

Menù Visualizza>Schermo intero oppure Ctrl+Maiusc+J.

Può essere comodo e si guadagna una discreta percentuale di visibilità, ma inibisce alcuni comportamenti quando si lavora con un (o più) prezzari aperti.

Al momento l'uso di LeenO in questa modalità visuale è sperimentale, perché, per usarlo, vengono disabilitati alcuni controlli (dovrei aver risolto... ma, al solito, fatemi sapere se incontrate problemi).

Attivando lo “schermo intero” spariscono menù e barre, compresa la barra del Sistema Operativo. Da quel momento si lavorerà solo sul Computo, concentrati come non mai...:-)

Ritengo comunque che i suoi comportamenti siano diversi a seconda del Sistema Operativo che si usa, ma, in genere, se si vuole vedere il resto del PC o usare un'altra applicazione è comodo prima ripristinare la visualizzazione standard. La cosa è rapida e indolore: Ctrl+Maiusc+J (si tratta di uno switch).

Comunque fate un po' di prove... il vostro window-manager vi mette a disposizione alternative diverse.

Per cambiare la visualizzazione si può anche usare la barra di ripristino della visualizzazione standard che appare quando si attiva lo “Schermo Intero”.

La cosa migliore è metterla in testa allo schermo, mettendo a lato la toolbar di LeenO.

### Filtri e ricerche

Il termine filtri potrebbe indurre dei fraintendimenti, perché LibreOffice dispone di diverse modalità di filtraggio delle tabelle.

Con LeenO ne ho sfruttate alcune.

#### Filtro Automatico sul Computo

Con la release 070220-V2 era stata aggiunta la possibilità di applicare un filtro automatico alla sola tabella di COMPUTO. Si Attiva e si Disattiva con Ctrl+Alt+F, (oppure dal menù LeenO>Filtro Automatico sul Computo).

Personalmente non lo uso, ma pesa poco in termini di codice e l'ho lasciato soprattutto per poter eliminare al volo un filtro automatico applicato a mano (l'eliminazione a volte risulta difficile...).

#### Filtro Standard Semplificato (Filtro per ricerche)

Con la release LeenO-3.1.11.oxt ho aggiunto un filtro semplificato, utile per effettuare ricerche veloci su Elenchi prezzi, Prezzari e Computo. Sfrutta le opzioni del Filtro Standard di LibreOffice.

Attivandolo con Maiusc+F3 viene richiesta l'immissione di una parola chiave; la tabella filtrerà soltanto le righe che contengono quella parola, nascondendo le altre. La ricerca viene effettuata solo sulla colonna descrizione.

Si attiva e si disattiva con Maiusc+F3 oppure dal menù LeenO>Filtro Standard Semplificato.

Purtroppo non trova le parole mandate a capo nella cella.

#### Filtra COMPUTO e fa una copia su altra tabella

Questa macro non ha parentele con i filtri di AOO e LibreOffice, ma è a mio avviso uno strumento utilissimo.
Funziona in questo modo: la tabella COMPUTO viene filtrata sulla base di alcuni tag (segni/sigle) e il risultato viene duplicato su una nuova tabella. I “Tag” vengono inseriti nelle colonne AF, AG, AH, AI dello stesso foglio di COMPUTO.

* Le colonne AF, AG contengono i capitoli e i sotto capitoli
* Le colonne AH ed AI sono disponibili per inserire tag arbitrari

Le colonne AH, AI (intestate come Tag A e Tag B) si visualizzano dal pulsante (in COMPUTO) [Viste]>TAG on/off.

Inserendo opportune sigle in quelle colonne si potranno velocemente stralciare gruppi di voci.

Tutte e quattro sono comunque utilizzabili per estrarre parti del computo che verranno duplicate automaticamente su una nuova tabella. La tabella ottenuta ha le medesime caratteristiche di una foglio COMPUTO, ma per poterlo utilizzare come tale è necessario rinominare questa tabella come “COMPUTO” (non prima di aver cambiato nome alla tab COMPUTO originale).

In questo modo si può ottenere velocemente uno stralcio, o estrarre un computo specialistico.

Si attiva dal menù LeenO>Filtra Computo e Fai una copia su altra tabella.

#### Ricerche

Il nostro applicativo, per ora, aggiunge poco o nulla alle opzioni di ricerca dell'interfaccia utente di AOO e LO: in merito la guida in linea e il materiale in rete sono piuttosto esaustivi.

Vorrei però spendere qualche parola sperando vi possano evitare alcune frustrazioni nell'uso.

Le ricerche in AOO e LO sono potenti, ma per questo complesse e facilmente ci si dimentica di spuntarne qualcuna o di impostare il giusto criterio.

Inoltre in LO hanno introdotto una ricerca semplificata che appare in basso nella riga di status; dal menù si raggiunge comunque la finestra di Cerca & Sostituisci, uguale (credo) a quella di AOO.

Quindi, se non trovate qualcosa che “dovrebbe esserci”, non disperate e controllate con cura le opzioni.

**FIXME**: inserire immagine

Uno degli errori più comuni riguarda la ricerca di dati sulla tabella corrente (li avevamo visti...) ma che stanno in realtà su un'altra tabella. Ovvero si lavora su tabelle con formule che prelevano i dati da altre tabelle, e quello che vediamo sono spesso stringhe di testo in realtà scritte da tutt'altra parte.

Ne è un esempio la descrizione di una voce di computo che in realtà è scritta in Elenco Prezzi ma viene visualizzata in COMPUTO mediante una formula: CERCA.VERT().

Se, stando su COMPUTO, vogliamo trovare una (o più) parole contenute nel testo della descrizione è indispensabile impostare Cerca in: Valori nella finestrella a discesa nella metà nascosta (Altre Opzioni...) della finestra del Cerca e Sostituisci.

Solo in quel modo abbiamo la possibilità di trovare la stringa se il testo che la contiene non è fisicamente presente in quella cella.

Concludendo, se usiamo la finestra di ricerca della toolbar introdotta da LO non avremo nessuna possibilità di trovare elementi “linkati”, perché è preimpostata su formule.

## ORGANIZZAZIONE DEL TEMPLATE

All'apertura di un file.ods di LeenO potete trovarvi in schermate diverse. La cosa dipende da come sono impostate un paio di Variabili Generali.

La prima da impostare a 1 è S1.H317 (per default è a 0, e in tal caso il file.ods si apre sul [menù PRINCIPALE (Alt+0)]).

Invece, da S1.H310 potete scegliere se “aprire” su COMPUTO o sulla schermata informativa “Dati di questo Documento”. Io consiglio quest'ultima perché su quella schermata avete sottocchio quanto vi serve per capire di che documento si tratta.

**FIXME**: inserire immagine

Questa schermata è divisa in tre parti:

* quella inferiore con i menù che ti portano in giro per il template...
* subito sopra nome e percorso del documento in uso e nome e percorso del DCC (“Documento di Contabilità Corrente”)
* la parte superiore, più complessa con i diversi dati del progetto inseriti in una griglia che prospetta anche i Piè di Pagina e gli header della Pagina[^18]

Nella schermata, le uniche celle editabili sono quelle in colore lilla, le altre vanno modificate da dati generali... ma è necessaria una premessa.

I dati sono suddivisi in due categorie:

* Dati del Progetto
* Dati specifici del Documento in uso (celle lilla)

Nella schermata compaiono tutti insieme, ma la distinzione fra i due tipi di dati non è marginale.

I Dati del Progetto sono quelli che ci si aspetta, ovvero: titolo del progetto, stazione appaltante – committente, progettista, etc... ovvero tutti quei dati che appartengono al progetto e e alla sua realizzazione che sono comuni a tutti i documenti del progetto (e della successiva gestione del cantiere)[^19].

Per modificare questi dati fate click su [Anagrafica Generale] e modificateli[^20].

Dati specifici del Documento (file in uso) sono invece quelli specifici del documento, ovvero di quella copia specifica del file.ods su cui si sta lavorando.

Ad esempio: il documento potrebbe essere una “copia” sulla quale si sta eseguendo una simulazione di SAL, come di una prova (in fase di progettuale) per verificare i costi di soluzioni alternative, oppure di un computo parziale sul quale viene elaborata solo una parte “specialistica” di impianti; intendo dire che possono esistere, per uno stesso specifico progetto, diverse copie del computo e tutte appartenenti allo stesso progetto.

I Dati specifici del Documento (Dati del Computo) sono, appunto, quella somma di informazioni che consentono di conoscere ed identificare quello specifico documento.

Queste informazioni sono annotabili sulla schermata Dati di questo Documento nelle celle a sfondo lilla.

I Dati del Progetto sono, invece, visibili sulle stessa schermata, ma risiedono da un'altra parte (sull'Anagrafica Generale) e non devono (non possono) essere modificati da qui.

In ogni caso, sia che apriate il documento su Dati di questo Documento che su [menù PRINCIPALE (Alt+0)], trovate in basso una serie di pulsanti utili per raggiungere direttamente le tabelle su cui lavorare.

Il [menù PRINCIPALE] (Alt+0 o Ctrl+0) rappresenta il nodo principale da cui raggiungere la maggior parte delle opzioni di LeenO[^21].

Pertanto, per navigare senza perdersi tra i menù a schermo di LeenO, conviene sempre tornare al [menù PRINCIPALE (Alt+0)].

Prima di entrare nell'uso vero e proprio di LeenO vorrei ancora introdurre una schermata:

[menù PRINCIPALE (Alt+0)]>[VARIABILI GENERALI (PREFERENZE)].

In questa schermata si possono condizionare i comportamenti di LeenO nelle diverse situazioni.

Se le cose vi vanno bene come le ho impostate ignoratela... e non cercatevi grane, altrimenti andate a quel sottomenù e modificate i valori delle Variabili![^22]

[^18]: Con Click sul Pulsante a dx [Aggiorna header e piè di pagina] gli stili di pagina verranno aggiornati con i dati che vedete nei campi corrispondenti

[^19]: Questi dati sono visibili nella schermata, ma sono residenti altrove, ovvero sulla schermata Dati di questo Documento (tabella M1) ci sono solo dei collegamenti (link) alla tabella specifica Anagrafica Generale. A sua volta la tabella Anagrafica Generale può essere collegata ad un documento esterno, che può essere utilizzato come “deposito” per quei dati. Ogni volta che si emette un qualsiasi documento di contabilità si può accedere a quei dati

[^20]: Giusto per complicarvi la vita: i dati potrebbero anche risiedere su un documento esterno ed essere visualizzati su [Anagrafica Generale] mediante un link...

[^21]: Alcune opzioni sono invece esclusivamente raggiungibili da LeenO che viene aggiunto (tra il menù Dati e Il menù Finestra) durante l'installazione della libreria macro di LeenO. Se non trovate qualcosa provate a cercarla lì.

[^22]: E' qualcosa di analogo alle Variabili di Sistema usate in AutoCAD.

### Scorciatoie di tastiera

In LeenO sono attive molte scorciatoie di tastiera (dette anche ShortCuts). Con queste scorciatoie, usate in alternativa a menù di schermo (pulsanti), al menù a tendina e alla toolbar, potete attivare una buona parte delle macro di LeenO (con maggiore velocità ed efficienza).

In pratica si sono rivelate una grana senza fine...:-(Sopratutto sui sistemi Mac dove il tasto Alt non è disponibile. Dopo una serie di cambiamenti spero di essere arrivato ad un ragionevole compromesso che credo renda usabili le scorciatoie di LeenO su tutti i sistemi.

Ora però, con l'introduzione di LibreOffice, la situazione rischia di ricomplicarsi... ma stiamo a vedere.

Per alcune macro ho attivato due o più scorciatoie diverse, in modo che almeno una di queste sia disponibile. Ho comunque potenziato il menù a tendina, inserendovi buona parte delle macro; ora, con quello, la toolbar e i pulsanti nelle tabelle, si dovrebbe poter eseguire comunque qualsiasi operazione.

Mi rimane il dubbio di aver comunque sovrascritto delle shortcuts che venivano utilizzate altrimenti... in tal caso fatemi sapere.

La situazione “dovrebbe” oggi essersi stabilizzata, ma per scaramanzia non riporto qui la tabella delle shortcut. Richiamatela dal file.ods di LeenO mediante Maiusc+F1 oppure dal menù Principale, (eventualmente stampate quella tabella e tenetela in vista).

In ogni caso, se sul vostro sistema una shortcut che vi sta a cuore non funzionasse, potete impostarla a mano. Per impostarla a mano dovete conoscere nome e percorso della macro; allo scopo ho predisposto l'elenco dei percorsi alla tabella Scorciatoie nella colonna E alla destra (Attenzione, potrebbe essere nascosta).

Per impostare una scorciatoia:

menù di AOO>Strumenti>Personalizza...>Tastiera, metti la spunta su OpenOffice (la default è su Calc).

Digitando la combinazione di tasti potete controllare cosa avete di libero e decidere a cosa agganciare la macro. Posizionati sulla combinazione scelta andate in basso...

Funzioni>Categoria>Macro di Openoffice>User … proseguendo con il percorso specifico della macro (quello sulla colonna E della tabella Scorciatoie) compreso il nome del modulo. Sulla destra in Funzione impostate il nome vero e proprio della macro. Poi date Cambia e poi OK. (spesso funziona soltanto dopo un reset di AOO o LibreOffice).

Nel caso si avessero ancora dei problemi con la registrazione delle scorciatoie è stata predisposta una procedura di manutenzione (da effettuarsi una tantum) che pare risolvere[^23]:

Menù Principale>Manutenzione (menù)>Forza la registrazione delle Scorciatoie da tastiera.

Il percorso sopra è disponibile solo dal template 161.3.7.

Attendere una trentina di secondi>poi salvare>chiudere AOO o LibreOffice (resettare anche il quickstarter)>riaprire il file.ods.

[^23]: Quelle stesse routine vengono eseguite durante la procedura di AGGIORNAMENTO DI UN COMPUTO “VECCHIO”

### ToolBar (icone)

Con la versione 3, oltre al menù a tendina LeenO, è stata aggiunta una toolbar con molte delle opzioni già presenti nel menù LeenO e/o nei pulsanti sui fogli. Portando il cursore su quelle icone appare una breve descrizione (tooltip) che aiuta a comprenderne l'uso.

**FIXME**: inserire immagine

Alcune di queste (es. VISTE) sono “contestuali”, ovvero a seconda del foglio su cui vi trovate vengono attivate azioni o dialoghi diversi.

### Com'è strutturato il Template

Gli elaborati contabili si articolano su una serie di tabelle contenute in un documento (file) “template“ che può avere nomi diversi.

Quello contenuto nello zip scaricato si chiama “Esempio_LeenO-xx.ods” Questo file può assumere qualsiasi nome vi faccia comodo.

Le tabelle principali sono:

* Elenco Prezzi - un magazzino dove sono raccolti:
  * i prezzi dei prezzari ufficiali
  * i prezzi ricavati con le Analisi di prezzo
  * i prezzi di mercato
* COMPUTO
* Analisi di Prezzo

	Attenzione:
    Queste tre tabelle sono collegate tra di loro: non modificate MAI il loro nome!

Poi ci sono le tabelle con i quadri economici, ma queste vanno e vengono... ciascuno avrà le sue preferenze e potrà costruire un quadro economico velocemente usando i noti sistemi che si usano nelle tabelle di calcolo (io ne lascio sempre un paio come esempio).

Poi ci sono un sacco di altre tabelle, ma normalmente sono nascoste e in genere servono ad LeenO per funzionare. Ne parliamo più avanti.

I Prezzari (i listini) ufficiali sono altri file, autonomi ed esterni al documento di lavoro.

Il file Esempio_LeenO-XXX.ods è quindi il file principale e i prezzari sono soltanto dei file accessori dai quali andremo a prelevare delle voci di prezzo per inserirle in COMPUTO.

Per questo devo introdurre un concetto fondamentale: quello del “Documento di Contabilità Corrente”, spesso abbreviato in DCC. Intendo dire che noi possiamo tenere aperte più file.ods di LeenO, ciascuno contenete il suo computo, ma una sola sarà quella del “Documento di contabilità Corrente” (DCC), ovvero uno solo sarà il documento di contabilità che stiamo elaborando!

Quando da un file prezzario vorremo inviare una voce al file.ods di LeenO, questa finirà sul DCC, e non su una delle altre copie eventualmente aperte[^24].

Per definire il DCC è sufficiente andare su Dati di questo Documento (Alt+0 o Ctrl+0 e cliccare su [Rendi corrente questo documento].

Da quel momento tutti i documenti aperti sulla scrivania (o comunque quelli che ne hanno bisogno) sapranno qual è il DCC su cui stiamo lavorando!

**FIXME**: inserire immagine

Il file.ods (Esempio_LeenO-XXX.ods) è composto da diverse tabelle (sheets, fogli...) ma, come i modelli cartacei classici (del secolo scorso), un computo metrico è formato sostanzialmente da due tabelle:

Un Elenco Prezzi (prelevati da Prezzari "ufficiali" esterni nel caso si parli di opera pubblica).

Un COMPUTO Metrico estimativo (dove sono elencati i vari lavori da eseguire, con le quantità, il prezzo unitario e il prezzo totale).

Succede spessissimo che per una certa lavorazione non si abbia il prezzo finito; in tal caso è necessario costruire un nuovo prezzo usando i costi dei materiali, della manodopera e degli eventuali trasporti e noli, a disposizione su un prezzario ufficiale o dedotti da indagini di mercato. Questo viene fatto su una terza tabella, denominata Analisi di Prezzo.

Ogni nuovo prezzo, così dedotto, deve essere registrato come nuova voce nell'Elenco Prezzi con l'apposito pulsante.

Ovviamente queste tre tabelle sono collegate fra loro. Per comprendere meglio la situazione potete usare Ctrl+F8 (o menù Visualizza>Evidenzia valori).

Al di là dei caratteri colorati che appaiono dopo questa operazione, e che hanno il solo scopo di comprendere la struttura dei collegamenti, LeenO fa un uso massiccio dei colori di sfondo delle celle.

Queste colorazioni (spesso tutt'altro che eleganti) hanno diversi scopi utili:

* leggibilità: distinguere una voce da un altra, capire dove bisogna immettere dati, etc...
* orientamento: sapere immediatamente su quale tabella siamo... qualcosa di simile alla “percezione” dell'ora su un orologio analogico rispetto ad un digitale.

In più noi abbiamo l'abitudine di aggiungere colori in giro come promemoria, aumentando – almeno apparentemente - l'ergonomia della visualizzazione del documento...[^25]:-)

Il documento stampato sarà stampato in totale assenza di colori, salvo esigenze particolari (un computo metrico di un'opera pubblica ha normalmente centinaia di pagine da stampare in molte copie e siccome siamo sull'orlo della bancarotta evitiamo di “stupire con effetti speciali”...).

Questo, in OpenOffice, rappresenta al momento una piccola complicazione, perché è privo dell'opzione "stampa ignorando i colori". (§ Stampa e manipolazioni finali).

In ogni caso LeenO è stato pensato perché l'utente possa modificare a piacimento i modelli di pagina o di cella (§ Stili e colori).

Su LeenO abbiamo ancora altre tabelle che normalmente sono nascoste (al momento M1, S1, S2, S3, ed S4 - non poniamo vincoli alla provvidenza...), sono tabelle di “servizio” che non fanno parte dei documenti del Computo Metrico e non devono essere stampate; vengono invece utilizzate da LeenO per fare delle cose, per depositarne altre, per appuntarvi formati di voce, oppure contengono dei menù grezzi ma efficaci (roba da archeologia informatica).

Ovviamente ciascuno potrà ancora aggiungere varie tabelle per i diversi Quadri Economici (a suo gusto e discrezione...), opportunamente linkate [^26] ai totali delle giuste tabelle (ma anche copia/incolla può andare... dipende dai gusti e dalle abitudini personali).

Direi che in questo caso si evidenziano le potenzialità proprie di un Computo su tabelle di calcolo.

Ancora qualche parola su quella riga rossa che sta al fondo delle tre tabelle principali (Elenco Prezzi, Analisi e COMPUTO). Questa riga rossa serve ad LeenO per individuare il margine delle tabelle.

Queste “righe rosse” possono essere nascoste o visibili, non ha importanza. A volte le vedrete a volte no; se vi danno fastidio nascondetele, ma non devono essere mai cancellate!

(Nel caso se ne perda una, o venga sovrascritta, è sufficiente posizionarsi su un punto qualsiasi della riga “giusta” in fondo alla tabella e poi inserirla (Menù a tendina LeenO>UTILITY>Inserisci riga rossa di chiusura).

[^24]: É il caso di una contabilità analoga di un altro progetto che si vuole consultare, oppure di un'altra copia dello stesso progetto (un backup o simili).

[^25]: Un altro modo per introdurre ulteriori annotazioni e commenti è: Inserisci>Commento. Durante la procedura di stampa, queste “note” verranno cancellate dalla procedura LeenO>STAMPA (procedure di)>1) PREPARA IL FOGLIO PER LA STAMPA insieme ai colori.

[^26]: Anche in questo caso si raccomanda l'uso di riferimenti assoluti al nome della tabella di origine ($nome_tab_origine.alfaxx). Questo per evitare sorprese quando si duplica il foglio e/o lo si manda in stampa usando le procedure di LeenO.

## L'ELENCO PREZZI

### Inserire un nuovo prezzo

Per inserire un nuovo prezzo da un Prezzario “ufficiale” occorre copiare/trasferire un blocco di informazioni (una voce per volta) da detto prezzario al nostro Elenco Prezzi.

E' necessario definire il file.ods in elaborazione come file/documento di “Contabilità Corrente”[^27] (abbreviato in DCC); per farlo devi andare sulla tabella M1 (Dati di questo Documento) usando Alt+4 e cliccare sul pulsante [Rendi corrente questo documento]. Il tutto al fine di individuare detto file come il file di destinazione dei dati che gli invieremo a partire dal prezzario esterno.

Poi serve un file di prezzario del tipo LeenO che trovate su [http://leeno.org/prezziari/download-prezziari/](http://leeno.org/prezziari/download-prezziari/) [^28] (questo sarà il file dal quale verranno inviati i dati al file in lavorazione).

Se utilizzate un prezzario suddiviso in capitoli, troverete all'inizio dell'elenco di voci, nel foglio Listino, un indice dei capitoli. Per aprire il capitolo che interessa è sufficiente selezionare il nome dall'indice e cliccare sul pulsante Apri altro capitolo... (§ PREZZARI – adattamento).

	Note:
    Tutti i file appartenenti ad un prezzario devono essere nella medesima cartella (Nulla vieta di tenere insieme in un'unica cartella tutti i prezzari che ci interessano).

Chi intende continuare ad utilizzare il prezzario completo in unico file può farlo, al costo di un fisiologico rallentamento dipendente dalla mole di dati gestiti e dalle potenzialità del PC a disposizione.

I file di prezzario hanno almeno due tabelle:

* Listino: il prezzario vero e proprio
* Temp: una tabella di servizio che serve per assemblare e/o modificare la voce [^29]

Il comportamento della procedura dipende da alcuni valori inseriti in specifiche celle.

Nella tabella di Listino potremo decidere:

* il livello di accodamento, che dipende dalla struttura del prezzario corrente, cambiando il valore nella cella G1 (i valori ammessi sono 1, 2 o 3)
* indicando nella cella I1 la scelta di inviare la voce direttamente al documento di “Contabilità Corrente” (DCC)[^30] senza passare dalla tabella di assemblaggio Temp

Nella tabella di Temp potremo decidere:

* se vogliamo che in fase di invio voce al DCC il codice-prezzo sia indicato anche nella sua descrizione  (Caso usuale di invio voce al DCC con codice arbitrario), indicando la nostra scelta nella cella H1

Andate sulla tab Listino, scegliete una voce di elenco e, dopo aver posizionato il cursore sulla riga contenente il relativo prezzo, cliccate sul pulsante [Assembla Voce]. La lavorazione verrà portata nella tabella Temp dalla quale si potrà scegliere se usare il codice originale del prezzario oppure sceglierne uno nuovo[^31].

Ora la voce è pronta da inviare a Elenco Prezzi del vostro documento di “Contabilità Corrente” (DCC). Per fare questo vi sono due possibilità corrispondenti a due pulsanti:

* [INVIA QUESTA VOCE ALL'ELENCO PREZZI (codici interni)] che copia la voce chiedendovi poi di inserire un codice alfanumerico di vostra scelta.
* [INVIA QUESTA VOCE ALL'ELENCO PREZZI (Codici originali del prezzario)] che copia la voce inserendo come codice prezzo la sigla originale del prezzario.

Se invece volete creare [^32] un nuovo prezzo nella tab Elenco Prezzi, compilando a mano la voce, potete inserire nell'elenco una riga vuota da: Viste>Crea Nuova Voce oppure: dalla toolbar (la N blu) o ancora con Ctrl+Maiusc+N.

	Note:
    Chiunque utilizzi i prezzari per LeenO avrà notato che non è possibile raggruppare le celle Dati>Raggruppa e struttura>Gruppo... (F12).
	Ringrazio Alberto Vallortigara per avermelo segnalato tramite il Forum.
	Non è del tutto vero. Il raggruppamento dei dati viene effettuato, ma non è possibile gestirlo se è disattivata la visualizzazione dei Punti di controllo.
	Dalla Guida di LibreOffice si legge:
	"Per accedere a questo comando…
	Aprite un foglio elettronico, scegliete Strumenti>Opzioni>LibreOffice Calc>Vista
	Punti
	Se avete definito una struttura, l’opzione Punti permette di visualizzare i punti corrispondenti sul bordo del foglio."

#### Note sul Codice Voce dell'Elenco Prezzi

Il codice usato nella colonna A dell'Elenco Prezzi è una “chiave primaria” e, in quanto tale, deve essere univoca poiché collega la tabella di Elenco Prezzi con quella del COMPUTO. Naturalmente nell'Elenco Prezzi posso coesistere codici proveniente da altri elenchi e codici nuovi (arbitrari): si può scegliere la modalità di codifica per ogni singola lavorazione quando, dal prezzario, si aggiunge la lavorazione all'Elenco Prezzi.

#### I Sommari dell'Elenco Prezzi

Nell'Elenco Prezzi è possibile ottenere, per ogni voce, la quantità totale prevista in COMPUTO per ogni specifica lavorazione. Allo stesso modo è possibile ottenere, per ogni voce di Elenco Prezzi, le somme delle lavorazioni già eseguite e annotate nel foglio di CONTABILITA.

Dalle [VISTE] del foglio Elenco Prezzi per visualizzare le colonne: toolbar>VISTE>Sommario COMPUTO On/Off oppure toolbar>VISTE>Sommario CONTABILITA On/Off. Per rigenerare i Sommari: Pulsante>VISTE>RI-GENERA Sommario del Computo oppure Pulsante>VISTE>RI-GENERA Sommario della Contabilità.

	Note:
    la somma totale dei valori della colonna L dell'Elenco Prezzi corrisponderà ovviamente al totale Computo (colonna S del COMPUTO). Questa colonna è utile per le modalità di offerta al ribasso che richiedono ultimamente alcune amministrazioni. Allo stesso modo c'è una corrispondenza precisa tra il totale dei valori della colonna O (dell'Elenco Prezzi) con il totale della colonna Z del foglio CONTABILITA.

[^27]: Sul desktop ci potrebbero essere anche diversi computi aperti, e si tratta sostanzialmente di impostare una “variabile di sistema” che informi il sistema di LeenO su quale documento deve essere “incollata” la voce del prezzario.

[^28]: All'indirizzo [http://leeno.org](http://leeno.org) potete scaricare altri prezzari.

[^29]: La buona parte dei prezzari sono organizzati in “struttura” su diverse righe. Esempio: tubi in cemento su una riga e diametro 5, diametro 10, etc su righe successive. Ma a noi serve una voce completa in unica cella tipo: tubi in cemento del diametro 10...

[^30]: Purtroppo alcuni prezzari sono un po' difettosi e non vi è modo di prelevare la voce completa in automatico. (ad esempio Piemonte: Sondaggi e Geognostica, Bioedilizia). In questo caso è necessario tornare sul listino, copiare la voce madre e incollarla aggiungendola alla descrizione incompleta. Alcuni listini hanno descrizioni ridondanti o errori di importazione e potete già correggere in quella sede (cella C3).

[^31]: Adottando dei prefissi mnemonici per le categorie principali, si può meglio costruire un ordine complessivo del computo (esempio se tutte le demolizioni hanno prefisso D, o W per gli impianti elettrici e così via).

[^32]: Esempio per inserire un “prezzo di mercato”

### Più colonne all'inizio dell'Elenco Prezzi

Questa opzione è stata temporaneamente disattivata!

Dopo l'aggiunta dei Sommari la cosa si è fatta troppo complessa Ma un paio di amici la considera fondamentale e stiamo lavorando per riattivarla.

Anche nelle parti di codice più recenti. Mi aspetto comunque qualche bug e/o refuso che cercheremo di chiudere prontamente.

A volte, avere la possibilità di aggiungere una o più colonne all'inizio dell'Elenco Prezzi può essere utile per riordinare secondo altri criteri.

Pertanto dalla versione 3.2.27 era stata introdotta la possibilità di aggiungere uno o più (fino a tre) colonne all'inizio dell'Elenco Prezzi (colonne A, B e C).

L'uso di queste colonne non interferisce con il normale funzionamento di LeenO, che continuerà a comportarsi secondo le normali procedure.

Ma sappiate che qualsiasi manipolazione di quella tabella (ad esempio riordinare in base alla colonna aggiunta) dovrà essere fatta manualmente.

Ovvero LeenO non ha strumenti per gestire quelle colonne, ma non è infastidito dalla loro presenza[^33].

#### Codici doppi in Elenco prezzi

I codici doppi in Elenco Prezzi non devono esistere, perché a codici eguali possono corrispondere prezzi diversi e le formule del COMPUTO prelevano il primo che trovano. Questo è un problema.

Creando una Analisi può succedere che si imposti un codice già in uso, ma in quel caso esiste un controllo automatico che individua l'errore appena si tenta di registrare l'Analisi come nuovo prezzo.

In ogni caso l'esecuzione LeenO>Trova Codici Doppi in El.Prezzi ci informa sull'esistenza di eventuali doppioni.

Se invece i doppioni derivano da un accodamento si può usare la macro: LeenO>Trova ed ELIMINA Codici Doppi in El.Prezzi.

La macro elimina automaticamente solo le voci identiche (tutti i campi della voce devono essere identici). Invece nel caso abbiano il medesimo codice, descrizione, etc, ma prezzo diverso, LeenO chiede conferma e/o istruzioni per l'eliminazione della voce superflua.

[^33]: Avevo inserito questa opzione su richiesta di alcuni utenti, ma poi me ne sono scordato e temo di aver fatto delle modifiche al codice che bloccano il funzionamento in quelle condizioni. In tal caso fatemelo sapere che valutiamo se vale la pena ripristinare.

### Aggiornamento dell'Elenco Prezzi con un Nuovo Prezzario

A volte succede che sia necessario rivedere il computo ed aggiornarlo con prezzario più recente. Si definisce in gergo “aggiornamento prezzi” ed è una di quelle operazioni che tutti vorrebbero poter fare in automatico.

In LeenO NON esistono automatismi per questa operazione e nemmeno saprei come farli usando tabelle di calcolo. In ogni caso ritengo che per un'operazione così delicata non ci si possa fidare ad aggiornare in automatico. Ritengo che l'onere di controllare voce per voce, senza l'ausilio di automatismi, non possa essere evitato.

In LeenO l'aggiornamento dei prezzi va effettuato importando nuovamente ogni singola voce dal nuovo Prezzario. Ovviamente la voce “Vecchia” va eliminata o disattivata ad esempio aggiungendo un suffisso al codice; in questo modo, al primo riordino dell'Elenco Prezzi, la voce vecchia verrà messa immediatamente dopo quella nuova e ci si sentirà meno confusi (la vecchia voce potrà essere eliminata anche in seguito).

Comunque il lavoro può essere reso più veloce operando in questo modo:

* Duplicare L'Elenco Prezzi vecchio nel file del prezzario più recente. (La cosa va fatta a mano in questo modo: clik destro sulla Tab dell'Elenco Prezzi>Sposta/Copia foglio - Spuntare copia - Selezionare il documento Prezzario>OK
* Nell'Elenco Prezzi del file della contabilità eliminare tutte le voci di Elenco Prezzi che arrivano da Prezzario (cioè vanno mantenute solo le voci che arrivano da Analisi di Prezzo, ovvero quelle con il tag (AP) nella colonna I)[^34]

Poi dal prezzario, per ciascuna voce:

* Selezionare la stringa del codice dall'Elenco Prezzi destro del mouse>Taglia (Tagliando il testo invece di copiarlo “teniamo il segno” dell'avanzamento)
* Andare sul foglio Elenco Prezzi, Ctrl+F e poi incolla nella finestrella del “Cerca”
* trovata la voce>Assembla voce>invia questa voce all'Elenco Prezzi[^35]

Per avere un maggiore controllo visivo potreste applicare alcune dei “trucchi” che trovate in Alcuni trucchi per l'accodamento.

E' probabile che alla fine, sul foglio del COMPUTO vi troviate con diverse voci con valori #N/D, ovvero voci con errori. Significa che vi siete 'persi' la voce di prezzo collegata; dovrete quindi andarla a cercare (utilizzando il solito codice voce) prima sull'Elenco Prezzi, e poi nel Prezzario.

In ogni caso, considerate che le voci dell'Elenco Prezzi derivanti da Prezzario sono state semplicemente duplicate dentro il foglio e non ci sono link e collegamenti. Quindi possono essere sottoposte ad operazioni di copia/incolla senza nessun problema.

Diverso invece per le voci dell'Elenco Prezzi che derivano da Analisi di Prezzo: quelle voci sono linkate e vanno trattate con molta cura ed attenzione.

Concludendo, un aggiornamento prezzi, anche se macchinoso alla fine non impegna una grande quantità di tempo. Il tempo si perderà invece (e inevitabilmente) per i ripensamenti ed a comprendere/correggere le inevitabili “stranezze” che si incontrano nel computo rivedendolo a distanza di tempo:-).

[^34]: Dipende da come avete impostato i codici, ma normalmente saranno tutte di seguito e l'operazione può essere facilmente effettuata a mano selezionando le righe interessate ed eliminandole.

[^35]: Nel caso non si trovi la voce (succede spesso per ragioni diverse) si dovranno usare usare altri criteri... la voce difficilmente sarà sparita... ma non si può escludere un errore dell'Ente che ha rilasciato il prezzario.

## L'ANALISI DI PREZZO

### Creare una voce di Analisi di prezzo (modello AVCP)[^36]

Con il rilascio della versione 3.9.0 è stato ricostruito il modulo di Analisi di Prezzo secondo i dettami dell'Autorità di Vigilanza sui Contratti Pubblici.

A differenza di altri sistemi tabellari usati per fare i computi metrici, con LeenO è previsto che tutti i prezzi ricavati con le analisi confluiscano nell'Elenco Prezzi insieme ai costi elementari (materie prime etc.).

Per creare una nuova voce di analisi: vai sulla tabella Analisi di Prezzo posiziona il cursore dove preferisci all'interno dell'area di lavoro e clicca su [N] (pulsante in alto a sinistra o l'icona con la N sulla toolbar). Viene creata una nuova voce vuota e viene seleziona la cella del codice.

Qui il codice dovete proprio inventarlo... ovvero scrivere una sigla per questo nuovo prezzo[^37]. Poi dovrete digitare la descrizione dettagliata della lavorazione e attribuire a questa una unità di misura. Il passo successivo è compilare le righe delle forniture e delle lavorazioni che concorrono alla formazione del prezzo iniziando dalla cella di colonna A; questa cella ha una finestra a discesa che consente di scegliere uno dei codici dall'Elenco Prezzi. Questo metodo è comunque superato dal Pesca... che consente di andare a cercare e prelevare il codice dall'Elenco Prezzi[^38]. Agendo su LeenO>Pesca...[^39] (oppure i tasti Crl+Ins, Ctrl+8, Ctrl+Alt+K) verrà portato in primo piano l'Elenco Prezzi dove potrai cercare la voce che ti serve[^40].

Una volta trovata, posiziona il cursore in qualsiasi punto della voce, ripeti il comando Pesca...e ti ritroverai sulla tua analisi con il codice voce già inserito. Adesso inserisci le quantità e poi passa al componente successivo.

Se il numero dei componenti l'analisi eccede la vostra necessità, eliminatele usando i normali comandi di AOO, con il pulsante [-Riga/e] o con le scorciatoie: Alt+Del oppure Ctrl+Del.

Se invece i componenti non bastano, aggiungeteli con il pulsante [+Riga] o dalla toolbar. Questa opzione ha due modalità possibili:

* la nuova riga avrà i campi vuoti
* la nuova riga avrà i dati identici alla voce sovrastante.

Scegliete la modalità che preferite commutando da 0 ad 1 (o viceversa) il valore della Variabile Generale (S1.H303) raggiungibile da [menù PRINCIPALE (Alt+0)]>[VARIABILI GENERALI (PREFERENZE)]

	Note:
	La formula nella “descrizione” del componente inizia con: =CONCATENA(" ";.......). Tra quelle virgolette potete inserire una ulteriore specificazione. Lo stesso vale per lo spazio tra le virgolette al fondo della formula. Anche la cella compresa fra la descrizione generale dell'analisi e i dettagli può essere utilizzata per annotazioni o specifiche.

Gli Oneri di Sicurezza vengono inseriti usando il pulsante [+%] o dalla toolbar. La relativa riga porterà la dicitura ”di cui Sicurezza afferenti l'Impresa”  e verrà trattata come dato fine a sé stesso, non coinvolto nel risultato del calcolo. Questa notizia sarà poi trasferita all'Elenco Prezzi per le successive trattazioni.

L'Analisi del prezzo sarà corretta quando il prezzo che compare sulla stessa riga della descrizione sarà coincidente al prezzo unitario offerto della riga L. In caso contrario potreste aver involontariamente manomesso l'integrità della scheda su cui state lavorando. Verificate e, nel dubbio, sostituitela con una nuova voce di analisi (sarà più facile risparmiare tempo e grattacapi).

Quando la voce di Analisi è completa la si può registrare aggiungendola all'Elenco Prezzi: posizionati sulla voce e seleziona [=> Elenco Prezzi] o dalla toolbar[^41].

Nell'aggiungere una Analisi (come nuovo prezzo) nell'Elenco Prezzi viene effettuato un controllo per evitare doppioni di Codice Prezzo[^42]. Nel caso il codice sia già presente in Elenco Prezzi, LeenO propone all'utente d'interrompere l'operazione per esaminare la situazione e decidere il da farsi. Nel caso si preferisca sostituire nell'Elenco Prezzi la vecchia voce di prezzo con quella nuova è sufficiente impostare a 1 la Variabile Generale S1.H314.

Le voci di Analisi possono essere spostate in altra posizione come quelle del COMPUTO oppure riordinate alfabeticamente in base al Codice Voce: [menù PRINCIPALE (Alt+0)]>[RIORDINA Le Analisi di Prezzo (In ordine alfabetico)]

[^36]: Do per scontato che si sappia cos'è una analisi di prezzo...
[^37]: L'Elenco prezzi si riordina automaticamente in ordine alfabetico. Se per le analisi si sceglie un un prefisso adeguato, queste saranno poi raggruppate nell'Elenco prezzi in modo ordinato.
[^38]: Potete comunque scrivere a manina, come in tutte le finestre a discesa del documento.
[^39]: E' la medesima già vista per prelevare il codice dal Computo Vedi la FAQ.
[^40]: Puoi usare tutti i mezzi che AOO ti mette a disposizione: Ctrl+F oppure Maiusc+F3
[^41]: Con la sola esclusione del codice-prezzo, tutte le modifiche che effettuerete in futuro sull'Analisi andranno a modificare la voce di Elenco prezzi corrispondente.
[^42]: L'esistenza di codici doppi genera errori nei conteggi del COMPUTO, peraltro difficili da individuare.

### Approfondimento sui % (Utili, Oneri, Spese, Sconti, Maggiorazioni, etc)

**FIXME**: obsoleto con il modello AVCP di analisi

In base alla dicitura scelta dalla finestrella a discesa, LeenO imposta un valore percentuale stabilito come Variabile Generale che può essere modificato in qualsiasi momento. In tal caso il valore cambierà automaticamente su tutte le analisi (anche in quelle già completate). Quindi, se la cifra percentuale non è quella che volete, occorre andare a modificare i valori delle celle S1.H319, S1.H320, S1.H321 e S1.H322, in Variabili Generali.

Premendo il pulsante di inserimento [+%] viene proposta una determinata % anziché un'altra (“Utili” anziché “Sconto” e così via). La tipologia di % proposta dovrebbe corrispondere alle vostre esigenze, altrimenti aprite la finestrella a discesa e selezionatene un'altra.

Il comportamento di questo automatismo può essere modificato lavorando su alcune Variabili Generali. Ad esempio, nel caso dobbiate inserire uno “Sconto” (ipotizzando che lo sconto sia sempre quello e debba essere ripetuto per una certa quantità di voci) da Variabili Generali, si imposta a 1 la cella S1.H325. Poi, nella cella S1.H324 impostate il valore della percentuale di sconto.

Sempre dalle Variabili Generali si possono modificare altri comportamenti, come avere “Spese ed Utili di impresa” accorpati anziché separati; in tal caso dovete agire sulla cella S1.H323 (tabella S1, raggiungibile da [menù PRINCIPALE (Alt+0)]>[Variabili Generali]), impostando il valore di quella cella a 0 oppure ad 1.

Se invece state lavorando su computi particolari vi sono altre opportunità. Ad esempio, se vi torna utile inserire in blocco di tre righe di “maggiorazione %” in un colpo solo è sufficiente andare nelle Variabili Generali e mettere a 3 il valore di S1.H327.
Se la combinazione non è quella che vi serve andate in S5 celle C52:C54, e dalle finestrelle a discesa selezionate le maggiorazioni adatte ai vostri scopi; al prossimo inserimento vi troverete prospettata la nuova situazione.

	Attenzione:
    La manomissione non attenta del foglio S5 può compromettere l'intero funzionamento di LeenO.

### Analisi "annidate"

Succede spesso che delle analisi utilizzino prezzi derivanti da altre analisi.

Esempio:

“Caricamento, trasporto e smaltimento dei materiali di risulta”

* Caricamento (prezzo elementare da prezzario)
* trasporto (prezzo elementare da prezzario)
* Oneri di smaltimento dei materiali di risulta (prezzo elementare da prezzario)

questa analisi diventa un nuovo prezzo di Elenco Prezzi e, a sua volta, questo nuovo prezzo potrà essere utilizzato per costruire altre analisi per lavori più complessi come la “demolizione di intonaci”.

“Demolizione di intonaco a mq compreso trasporto e smaltimento”

* demolizione di intonaco (prezzo elementare da prezzario)
* Caricamento, trasporto e smaltimento (derivante da analisi)

Questa nuova voce di prezzo, a sua volta, potrebbe essere utilizzata per voci ancor più complesse come ad esempio:

“Rifacimento di intonaco comprensivo della demolizione del vecchio, del caricamento, trasporto e smaltimento...”

Ecco, questo intendo per Analisi annidate (qualcuno le chiama Centrali di prezzo).

LeenO supporta 5 livelli di “annidamento”, ma **ritengo conveniente rimanere entro il 3° livello**.

### Incidenza manodopera

Sulle 4 tabelle di lavoro le colonne delle incidenze della manodopera possono essere visualizzate/nascoste dal dialogo [VISTE].

La percentuale dell'incidenza viene gestita già dai prezzari (solo le versioni>a T3[^43]), poi nell'Elenco Prezzi, nelle Analisi, nel Computo, nella Contabilità e nel Sommario con le solite modalità degli altri dati.

Volendo ottenere i subtotali dell'incidenza manodopera anche dei SottoCap si deve impostare a 1 la variabile S1.H334. (Tutti i subtotali dell'incidenza manodopera vengono annotati solo nella colonna AP e non sulle righe).

Se i prezzi elementari di Elenco Prezzi contengono già l'incidenza della manodopera questa viene gestita automaticamente. Altrimenti, nel caso vi serva, bisognerà stimarla ed aggiungerla[^44]. In ogni caso, anche se il prezzario non la riporta[^45], aggiungere 100% alla manodopera già nell'Elenco Prezzi vi fa risparmiare tempo nel fare le Analisi.

[^43]: In teoria solo i prezzari con sigla T3 consentono di prelevare (l'eventuale) incidenza della Manodopera. Ma in pratica ho smesso di scrivere il suffisso da almeno un paio d'anni...
[^44]: La cosa più comoda è impostarla nell'Elenco Prezzi, ma.forse occorre una nota legale che specifichi che quell'importo (o%) è stato stimato e non appartiene al prezzario originale di riferimento.
[^45]: Si tratta, sotto il profilo formale, di una alterazione (manomissione) di un Prezzario ufficiale, ma IMHO e in pratica accettabile

### Gestione della Sicurezza

Con LeenO 3.8.36 (template 178) è stata introdotta la gestione della Sicurezza in tutte le fasi di progettazione e di cantiere. Non si tratta di una situazione ottimale perché la colonna della Sicurezza non è sempre dove la vorremmo, ma è una soluzione onorevole, e abbastanza pratica da gestire. Come per le incidenze Manodopera nelle tabelle di lavoro le colonne vengono visualizzate/nascoste mediante il noto dialogo (pulsante) [VISTE].

I prezzari che riportano dati sulla sicurezza sono ancora pochi, e a volte la riportano come percentuale, altre volte come importo (incluso nel prezzo). A causa della lamentata carenza di colonne ho scelto di gestire (in automatico) direttamente e solo l'importo, anche nel caso il prezzario riporti invece una percentuale.

Nel prezzario abbiamo la colonna J riservata per l'importo e la colonna K riservata per la percentuale. Se si ha l'accortezza di posizionare i dati nel posto giusto, il codice si occuperà poi di gestire automaticamente le cose. Le difficoltà maggiori rimangono quelle derivanti dall'interpretazione della normativa, ma a quanto ho capito, sostanzialmente richiede una visione analitica della sicurezza, sia per quella compresa nei prezzi delle normali lavorazioni, sia per quella specifica prevista nel piano di Sicurezza[^46].

Con LeenO la Sicurezza può essere gestita analiticamente in tutte le sue tabelle di lavoro.

Alla fine, ad ogni SAL si potrà prelevare il totale degli importi della sicurezza ricompresi nelle opere che si vanno a pagare e trattare i dati finali di conseguenza.

In caso si volesse invece ragionare per categorie mi pare ancora più semplice. E' infatti sufficiente attribuire un importo/percentuale pari al 100% alle voci classificate come Sicurezza. Poi, come sopra, ad ogni SAL si potrà prelevare il totale degli importi della sicurezza ricompresi nelle opere che si vanno a pagare.

[^46]: Non entro in merito alla questione se il solo nolo del ponteggio rientri o meno fra gli oneri della sicurezza, e debba o meno essere assoggettato a ribasso. Ma vorrei tanto vi fosse maggiore dibattito attorno a queste questioni.

## IL COMPUTO METRICO

