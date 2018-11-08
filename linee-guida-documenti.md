[Indice](index.md) / [Regole da seguire](regole-da-seguire.md)

# Stesura di documenti accessibili

## Regole generali per la stesura di un documento

* Organizzare la struttura logica del documento utilizzando stili di paragrafo che caratterizzino semanticamente i contenuti a cui vengono attribuiti;
* Collegare esplicitamente le didascalie all’immagine a cui si riferiscono tramite numerazione sequenziale contestualizzata all’organizzazione del documento;
* Non veicolare informazioni esclusivamente tramite immagini: i files così creati sono difficilmente leggibili tramite screen reader sempre se le immagini non sono supportate da testo alternativo. Per testo alternativo si intende una descrizione testuale che deve essere tanto più accurata quanto più l’immagine è parte integrante dei contenuti. Si può omettere la descrizione testuale dell’immagine se la stessa è già commentata nel documento.
* Quando si salvano/esportano documenti prodotti con programmi di office automation in documenti PDF, ricordarsi di abilitare nelle opzioni di salvataggio di esportare i “Tag per la struttura del documento per l'accessibilità”: questa opzione permette di includere nei files pdf le informazioni necessarie per creare documenti accessibili strutturati;
* Non utilizzare ritorni a capo, tabulazioni o spaziature per creare il layout desiderato del documento: vanno invece usati i comandi di interlinea, rientro o allineamento previsti dal programma elaboratore di testi. Molti screen reader o strumenti di sintesi vocale interpretano un ritorno a capo (segno di paragrafo immesso tramite il tasto “Invio”) come un’interruzione di frase e quindi fanno una “Pausa”, mentre ignorano i ritorni a capo dettati dal layout del documento.
* Utilizzare un “sommario navigabile” in testi lunghi o complessi: in testi lunghi o complessi, per rendere il documento più “usabile”, è bene dotarlo di un sommario navigabile che permetta di individuare più velocemente gli argomenti di interesse;
* L’accento non può essere sostituito dall’apostrofo, anche perché ciò produce un’errata cadenza della frase negli screen reader; quindi non «accessibilita’» bensì «accessibilità»;
* Evitare l'accumulo indiscriminato di informazioni: va organizzata una gestione ragionata dei contenuti, che non significa scrivere e pubblicare meno, ma ordinare, catalogare, filtrare, richiamare all'occorrenza tutti i contenuti collegati, in altre parole: un'ecologia delle informazioni. I “lenzuoli” testuali portano l'utente ad effettuare un’estenuante ricerca dell'informazione necessaria
* Aggiornare le informazioni obsolete: se il sito contiene informazioni che cambiano nel tempo, si devono tenere aggiornate costantemente e rimuovere quelle vecchie, creando eventualmente un archivio.

## Regole specifiche per migliorare la leggibilità di un testo

* Per quanto possibile evitare il corsivo: l’utilizzo del corsivo enfatizza l’effetto “sega” creato dai pixel discreti, qualora il testo venga ingrandito e di conseguenza peggiora la leggibilità del testo. Indipendentemente dal tipo di font e dal colore, il corsivo aumenta i tempi medi di lettura di un documento.
* Per quanto possibile evitare paragrafi troppo lunghi e l’allineamento giustificato: testi troppo lunghi all’interno di un singolo paragrafo e giustificati rendono meno leggibile il testo e affaticano di più la
vista, specialmente quando si utilizzano caratteri molto grandi e risoluzioni basse. È meglio utilizzare più paragrafi corti, spaziati tra di loro all’interno della pagina ed allineati a sinistra;
* Evitare testi lunghi in caratteri maiuscoli: si è verificato sperimentalmente che la leggibilità di un testo scritto esclusivamente in caratteri maiuscoli è minore di quella di un testo scritto in caratteri maiuscoli e minuscoli.
* La dimensione ottimale dei caratteri è di 12 punti (pt), mentre l’interlinea ottimale è compresa tra 1,2 e 1,5: da esperimenti condotti, i testi sono più leggibili. Caratteri troppo piccoli rendono il testo di difficile lettura, soprattutto a chi ha problemi di vista. Quanto al tipo di carattere (font), la scelta migliore dipende dal mezzo su cui è pensata la diffusione del documento:
  * su uno schermo sono più efficaci i caratteri cosiddetti “senza grazie” (esempi: Verdana, Arial)
  * su un testo stampato, invece, risultano più leggibili i caratteri “con grazie” (esempio: Times New Roman)
  * vanno evitati, salvo casi particolari, i font “monospaziati” o a larghezza fissa (esempio: Courier New)
* Fare in modo che gli sfondi siano semplici. Il bianco o i colori chiari in genere sono i migliori. Evitare sfondi con “Texture” perché appesantiscono il file e non sono leggibili dagli screen reader, inoltre ci si troverebbe a lottare con i contenuti della pagina per avere l'attenzione del lettore. Se si vuole usare un'immagine di sfondo, sceglierne una con colori sobri (non saturi o caldi) o impostata in trasparenza.
* Scegliere colori del testo che contrastano bene con l'immagine di sfondo: i colori, all'interno di una pagina web, devono rispettare precisi standard al fine di evitare problemi a chi soffre di disturbi legati alla visione dei colori, come il daltonismo. CheckMyColours è un semplice tool online che, dopo aver inserito l'url della pagina che si vuole analizzare, mostrerà una lista dettagliata contenente tutti gli elementi della pagina e, per ognuno di questi, un accurato test per la verifica dei singoli colori in grado di affermare se il colore in questione rispetta le linee guida in termini di contrasto e luminosità.
* Non utilizzare troppi colori nella stessa pagina: anche testi con troppi colori diversi creano difficoltà visiva nella lettura. Collegamenti dal colore insolito possono causare confusione tra i nuovi utenti.

## Regole tipografiche (valide solo per documenti in lingua italiana)

* Non inserire mai più di uno spazio fra parola e parola;
* Nella maggior parte dei casi i segni di punteggiatura vanno sempre attaccati alla parola precedente e staccati da quella successiva. Fanno eccezione:
  * Le aperte parentesi e le aperte virgolette (di tutti i tipi): vanno staccate dalla parola precedente e attaccate a quella successiva
  * Il trattino (breve), l’apostrofo e la barra separatrice: vanno attaccati sia alla parola precedente che a quella successiva
  * Il trattino lungo incidentale: va staccato sia dalla parola precedente che da quella successiva

## Regole specifiche per la scrittura su sito web

* Fornire il documento di un sommario navigabile che permetta il collegamento diretto ai corrispondenti contenuti e prevedere idonei collegamenti ipertestuali per il ritorno all’indice o ai contenuti alla fine di ciascuna sezione;
* Dotare gli elementi informativi a corredo del testo, tra i quali note e relativi rimandi e riquadri di approfondimento, di collegamenti ipertestuali espliciti al punto o all'elemento corrispondente nel testo principale;
* È buona norma indicare nei collegamenti (link) che permettono di scaricare files la dimensione del file e, se si tratta di file compressi, il formato nativo. I link vanno comunque realizzati prevedendo tutte le informazioni che normalmente costituiscono un collegamento accessibile, ovvero:
  * si deve garantire che tutti gli elementi informativi e tutte le funzionalità siano disponibili anche in assenza del particolare colore utilizzato per presentarli nella pagina (requisito 4 previsto dal DM 183/2005 – Attuazione “Legge Stanca”)
  * si deve inoltre rendere chiara la destinazione di ciascun collegamento ipertestuale con testi significativi anche se letti indipendentemente dal proprio contesto oppure associare ai collegamenti testi alternativi che possiedano analoghe caratteristiche esplicative (requisito 19 previsto dal DM 183/2005)
  * si devono infine prevedere meccanismi che consentano di evitare la lettura ripetitiva di sequenze di collegamenti comuni a più pagine (requisito 19 previsto dal DM 183/2005)
* Potrebbe essere buona prassi aggiungere il link che permette di scaricare l’applicativo necessario per la sua visualizzazione
* Nel caso di pagine html che si aggiornano automaticamente (anche mediante DHTML) o con un contenuto “a tempo” sarà necessario fornire una pagina alternativa in cui tale aggiornamento non avvenga automaticamente, ma solo mediante la selezione di un link.
* Non inserire collegamenti che non funzionano o che puntano a pagine sbagliate. Evitare inoltre i collegamenti lunghissimi che non dicono all'utente dove portano o di cosa trattano.
* Evitare di inserire pagine introduttive statiche o animate in Flash: pregiudicano l'accessibilità del sito e spesso rappresentano un'inutile perdita di tempo, soprattutto per i visitatori abituali del sito. La pagina d'introduzione esiste già: si chiama “Home Page” e non è solo la prima pagina del sito, da cui l'utente può raggiungere le diverse sezioni, ma è soprattutto la pagina in cui si presenta il sito con le sue funzionalità. Le animazioni con Flash hanno spesso un peso non indifferente che ha come conseguenza diretta un caricamento molto rallentato. Non tutti i navigatori inoltre sono muniti di flash, non tutti i computer reggono un'introduzione, non tutti sono capaci di far scorrere la rotellina per visualizzare il tasto “salta l'introduzione” che si trova sotto il blocco che conterrà l'animazione.
* Non inserire testi scorrevoli e gif animate: le animazioni continue o lampeggianti all'interno di un sito pregiudicano l'accessibilità del sito. Ecco i principali motivi per non usare questi elementi:
  * violano il Requisito 2.3 previsto dalle linee guida WCAG 2.0 (Evitare oggetti e scritte lampeggianti o in movimento le cui frequenze di intermittenza possano provocare disturbi da epilessia fotosensibile o disturbi della concentrazione, ovvero possano causare il malfunzionamento delle tecnologie assistive utilizzate)
  * sono causa di convulsioni nei soggetti che soffrono di epilessia fotosensibile ed è pertanto un punto importante nell'adeguamento alla legge sull'usabilità;
  * l'utente viene distratto. La maggior parte dei contenuti sul web è testo e l'utente deve fare uno sforzo per leggere. Avere un tipo che gli balla a destra e un blocco di testo che lampeggia a sinistra non è il massimo. Per restare concentrati, infatti, le persone lo trovano fastidioso, oltre che a concepirlo come un “pericolo”;
  * sebbene questi elementi dovrebbero avere lo scopo di richiamare l’attenzione del visitatore su un particolare aspetto della pagina, gli elementi che lampeggiano sembrano banner e gli utenti tendono ad evitarli;
  * con le ultime versioni degli screen reader, gli utenti con disabilità della vista leggono testi in movimento come quelli generati dagli applets e dai javascripts, ma ne sono totalmente incapaci se navigano in Internet con strumenti di ausilio più vecchi: occorre quindi, in linea di massima e per consentire accessibilità a tutti i non vedenti, fornire testi alternativi per tutte le scritte contenenti elementi in movimento o lampeggianti
  * le ultime specifiche del W3C non includono l’uso dei codici MARQUEE e BLINK (i marcatori HTML utilizzati per la realizzazione di tali testi)
* Non inserire musica di sottofondo:
  * gli utenti navigano spesso da uffici e luoghi pubblici e i dispositivi sono dotati di casse. Ovviamente se partono dei suoni non richiesti possono dare fastidio;
  * un suono improvviso può spaventare i visitatori del sito;
  * se l'utente sta navigando più siti contemporaneamente non saprà immediatamente da quale sito arriva il suono e quando lo saprà non si farà scrupoli a chiudere la scheda;
  * qualora l’inserimento del suono dovesse pure risultare significativo, l’utente potrebbe non essere in grado di sentirlo, perché disabile (sordo) o equipaggiato con un dispositivo incapace di riprodurre l’audio
* Evitare di utilizzare strutture di navigazione complesse: una struttura di navigazione facile da usare è essenziale per qualsiasi sito ben progettato. Informazioni importanti dovrebbero essere raggiunte in non più di due click.
* Evitare anche le Home Page troppo lunghe: se le notizie possono essere classificate è certamente meglio creare altre voci di menù con link diretti alle categorie interessate. In questo modo eviteremo di far stancare eccessivamente l'utenza, permettendo alla stessa di giungere alla destinazione di interesse in breve tempo.
* Nel realizzare la rete dei collegamenti, fare in modo che sia sempre possibile tornare sui propri passi, senza che sia necessario premere il tasto “Indietro” sul browser.
* Evitare di sottolineare il testo: induce il navigatore a cercare un link.

## Regole specifiche per migliorare la fruibilità a persone disabili

* Garantire che il corretto ordine di lettura sia preservato anche quando il testo eventualmente suddiviso in blocchi o in colonne venga presentato in modo linearizzato;
* Evitare di utilizzare immagini o altri elementi grafici per rappresentare contenuti testuali;
* Non creare documenti da scansioni (PDF immagine): i PDF immagine non sono fruibili dalle persone non vedenti ed il testo al loro interno non è ricercabile. Pur potendo utilizzare strumenti di riconoscimento del testo (OCR), nei files così creati possono esserci errori dovuti a problemi di conversione del testo o alla difficile interpretazione delle tabelle da parte degli OCR;
* Non veicolare informazioni esclusivamente tramite il colore (si consideri, in proposito, il Requisito 1.4 delle linee guida WCAG 2.0): gli screen reader ignorano i colori all’interno di un testo inoltre alcuni colori possono creare difficoltà a chi utilizza il proprio “residuo visivo” per leggere a schermo, con o senza l’ausilio di programmi ingrandenti. Si deve dar la possibilità di modificare i colori del testo e sfondo liberamente;
* Tabelle: le tabelle permettono di rappresentare in modo molto efficace diverse tipologie di dati tra loro correlati. Quando la consultazione di una tabella non avviene attraverso la vista possono sorgere problemi di comprensione della stessa e di accessibilità; vanno definite le celle che compongono la tabella differenziando quelle del titolo dai dati con gli appositi strumenti. Quando possibile, le tabelle andrebbero “linearizzate” cioè convertite in una serie di paragrafi che contengono, uno dopo l’altro, i contenuti delle celle della tabella (la cosa viene fatta
automaticamente dagli screen reader). Tabelle annidate o troppo complesse, oltre a rallentare i tempi di caricamento del testo, sono praticamente impossibili da consultare per disabili non-vedenti, che utilizzano browser testuali e screen-reader per navigare.
* Grafici: i grafici che contengono valori vanno trattati alla stregua delle tabelle, cercando cioè di “linearizzare” i loro contenuti; per i grafici che non contengono valori, o che sono di difficile estrapolazione, bisogna cercare di tradurre in testo il messaggio che il grafico vuole dare visivamente al lettore.

## Regole specifiche per migliorare la comprensibilità del testo

* Dotare le immagini, i grafici e le tabelle di didascalie esaurienti, che forniscano informazioni equivalenti commisurate alla funzione esercitata dall’oggetto originale nello specifico contesto;
* Non utilizzare sigle senza spiegarle.

## Regole per il miglioramento dell’usabilità

* Non inserire immagini troppo pesanti: ridimensionare le immagini (utilizzando eventualmente anche strumenti gratuiti online) prima di inserirle all’interno dei documenti. Le loro dimensioni inoltre non devono essere molto superiori a quelle che occuperanno nella pagina stessa, a meno che la funzione zoom ne consenta l'ingrandimento: spesso all’interno dei files invece vengono ridimensionate solo visivamente (altezza e larghezza dell’immagine), ma il peso rimane invariato (dimensione in byte dell’immagine);
* Mantenere la dimensione del file ridotta: un file di grandi dimensioni può essere difficile da gestire per computers non di ultima generazione o con connessioni internet lente (nel caso il documento sia messo a disposizione tramite internet);
* Inoltre è bene suddividere documenti di grandi dimensioni in più documenti (per esempio la suddivisione in capitoli facilita il reperimento di punti specifici all’interno di un documento complesso) anche perché se convertito in audio un documento di grandi dimensioni risulterebbe un file audio enorme, scomodo da usare;
* Immagini che non si caricano correttamente possono essere causate dall'errato upload dei files o da caratteri sbagliati nel nome o da formati o estensioni insolite.

## Altro

* Garantire che i contenuti sottoposti a ingrandimento siano visualizzati nel rispetto dell’ordine di presentazione originale ed evitare che per la loro lettura si debba ricorrere alla barra di scorrimento orizzontale del programma di lettura utilizzato.
* Ricordarsi di inserire in Home Page i dati rilevanti relativi all'Ente: indirizzo, telefono, mail, orari di apertura al pubblico… (Contatti)
* Evitare di duplicare i menu
* Evitare di utilizzare mappe stradali statiche copiate da GoogleMap come immagini, al posto di Mappe dinamiche. Va ricordato tuttavia che anche l’incorporamento delle mappe avviene attraverso IFRAME (Inline Frame), non proprio uno strumento accessibile
