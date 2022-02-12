---
hide:
  - toc
og_title: Come vorri che fossero pubblicati i dati della pubblica amministrazione
og_image: comeLiVorrei.png
description: L'amministrazione, di concerto con la collettività, deve in prima istanza individuare e scegliere quei dati che, una volta resi pubblici, possano generare valore per la collettività stessa
---

# Come li vorrei

*di [Andrea Borruso](https://twitter.com/aborruso), [Giorgia Lodi](https://twitter.com/GiorgiaLodi), [Paola Chiara Masuzzo](https://twitter.com/pcmasuzzo), [Davide Taibi](https://twitter.com/dataibi)*

Quando offriamo un bicchiere d’acqua del rubinetto di casa a un nostro ospite, non diciamo “ecco un bicchiere d’acqua potabile”. Allo stesso modo, quando si parla di dati, vorremmo che l’aggettivo “*open*” fosse sottinteso.
Così come diamo per scontato che l’acqua di casa sia potabile, vorremmo poter pensare lo stesso per quanto riguarda i dati pubblici.

Ma i dati, proprio come l’acqua potabilizzata, per essere accessibili e aperti necessitano dell’intervento della politica e dell’amministrazione.

La politica deve decidere l’apertura dei dati di pubblico interesse.

L’amministrazione, di concerto con la collettività, deve in prima istanza individuare e scegliere quei dati che, una volta resi pubblici, possano generare valore per la collettività stessa; la pubblicazione e la conseguente diffusione di questi dati devono seguire i più elevati standard internazionali.



## I principi FAIR

Un *framework* concettuale di grande importanza è quello dei principi **FAIR**, un insieme di linee guida formulate nel 2014 per ottimizzare la pubblicazione, la riutilizzabilità, e la qualità dei dati di ricerca, ma che si può, anzi si deve, estendere a tutti i dati di interesse pubblico. I principi FAIR si possono riassumere come segue:

  - **Findable (Trovabile)**: i dati devono essere facilmente **rintracciabili** dagli esseri umani e dalle macchine. Questa proprietà è garantita dall’uso di identificatori persistenti (PID) (DOI, Handle, URN), e dai metadati^[ℹ️](glossario.md#metadati)^ descrittivi, che devono essere registrati in "cataloghi" o in *repository* indicizzabili anche dalle macchine.

  - **Accessible (Accessibile)**: i dati devono essere sempre **accessibili**, persistenti nel tempo, e rintracciabili in rete, attraverso protocolli standard. Qualora non fosse possibile rendere i dati “*open*”, sistemi di autenticazione possono essere usati, a patto che almeno i metadati siano sempre disponibili.

  - **Interoperable (Interoperabile)**: i dati (e i metadati) devono essere **interoperabili**, ovvero devono poter essere combinati con altri dati e strumenti. Questo vuol dire che il loro formato deve essere aperto^[ℹ️](glossario.md#formato-aperto)^ (un *CSV* lo è, un *XLS* no), e che i metadati di contenuto e descrittivi devono essere rappresentati in un linguaggio standardizzato (usare ontologie e vocabolari controllati, ove possibile).

  - **Reusable (Riutilizzabile)**: i dati devono essere **riutilizzabili**, per cui deve essere chiaro in che modalità sia dati che metadati possono essere riutilizzati (replicati, usati in contesti diversi, con scopo diverso, etc). Questo significa anche accompagnare i dati con una o più licenze aperte^[ℹ️](glossario.md#licenza)^, chiare, accessibili e possibilmente riconosciute a livello internazionale.

I principi FAIR sono, per l’appunto, dei principi. Agnostici da implementazioni tecnologiche, costituiscono delle linee guida per garantire non solo che dati/metadati siano rintracciabili e persistenti nel tempo, ma anche che siano pubblicati tenendo in mente standard internazionali di rappresentazione del dato di alta qualità.

Alcuni di [questi](http://www.iso25000.it/styled-19/), anche referenziati nelle [linee guida nazionali per la valorizzazione del patrimonio informativo pubblico](https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/aspettiorg.html#qualita-dei-dati), hanno tra i loro obiettivi la valutazione dei requisiti di qualità dei dati nella produzione, acquisizione e loro integrazione, così come il miglioramento della qualità dei dati da esporre in modalità "Open data".

## La qualità dei dati

Anche rispetto ai principi FAIR prima enunciati, si ritiene importante riportare di seguito alcune caratteristiche di qualità dei dati, che vorremmo vedere implementate:

  - **Accuratezza**: di solito riferita sia all’accuratezza sintattica sia a quella semantica, consente di verificare se il dato rappresenta correttamente il valore reale del concetto o evento cui si riferisce. Questo facilita il raggiungimento degli obiettivi come definiti nei principi FAIR *Interoperable* e *Reusable*.

  - **Attualità**: il dato è del “giusto tempo” (è aggiornato) rispetto al procedimento cui si riferisce. Questa caratteristica di qualità è molto importante, è uno dei grossi problemi che affligge i dati aperti italiani e può anche riferirsi alla cosiddetta tempestività di aggiornamento del dato. Inutile evidenziare che se i dati non sono attuali, disponibili al giusto tempo, i principi FAIR Accessible, *Interoperable* e *Reusable* non riescono a essere pienamente soddisfatti.

  - **Completezza**: il dato risulta esaustivo per tutti i suoi valori attesi (ad esempio, un dato nazionale dovrebbe coinvolgere i dati di tutte le sue regioni, o ancora il dato sui contagi nelle scuole dovrebbe contenere la stato di tutte le scuole individuate per il monitoraggio) e rispetto alle fonti che concorrono alla sua creazione (ad esempio i dati aperti sui bandi pubblici dovrebbero integrare i dati provenienti da tutte le istituzioni che pubblicano bandi). Questa caratteristica di qualità concorre al raggiungimento degli obiettivi *Accessible*, *Interoperable*, *Reusable* e *Findable*, in quest’ultimo caso quando applicata ai metadati. Infatti, anche i metadati, che accompagnano i dati, devono essere il più completi possibile per contribuire a migliorare e facilitare la scoperta dei dati.

  - **Disponibilità**: il dato è disponibile e quindi viene consentito l’uso dello stesso da parte di utenti (autorizzati) e dalle applicazioni. Tale caratteristica rappresenta l’essenza di quanto indicato nel principio FAIR *Accessible* ma può essere di particolare rilevanza anche per il principio *Findable*: senza disponibilità dei metadati che descrivono i dati, scoprirli diventa molto più complesso.

  - **Portabilità**: anche uno dei diritti sanciti dal [regolamento europeo sulla protezione dei dati personali](https://www.garanteprivacy.it/il-testo-del-regolamento) (GDPR), consente di valutare la capacità del dato di essere trasportato da diversi sistemi in un formato strutturato e leggibile da una macchina. In questo caso, solo se il dato è interoperabile (*Interoperable*), si può effettivamente garantire tale caratteristica.

  - **Conformità**: questa caratteristica di qualità consente di valutare se il dato aderisce a standard, convenzioni, regolamenti (ad esempio come possono essere ontologie e/o vocabolari controllati). Questa caratteristica facilita il raggiungimento degli obiettivi previsti per i principi *Interoperable* e *Findable*, in questo ultimo caso se i metadati per esempio seguono standard condivisi anche in contesti non necessariamente nazionali.

Si vuole infine evidenziare la necessità di uniformarsi alle linee guida nazionali per la valorizzazione del patrimonio informativo pubblico che, attraverso le [azioni riportate](https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/riepilogoazioni.html), raccomandano anche [piccoli accorgimenti](https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/arch.html#formati-aperti-per-i-dati-e-documenti) (come ad esempio specificare il carattere separatore quando si pubblicano CSV, ecc.), utili a garantire un processo di gestione dei dati di qualità.

!!! info "Riferimenti utili<a name="riferimenti-utili">&nbsp;</a>"

      - DECRETO LEGISLATIVO 24 gennaio 2006, n. 36 - Attuazione della direttiva (UE) 2019/1024 relativa all'apertura dei dati e al riutilizzo dell'informazione del settore pubblico che ha abrogato la direttiva 2003/98/CE ([🔗](https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2006-01-24;36!vig))
      - DECRETO LEGISLATIVO 7 marzo 2005, n. 82 - Codice dell'Amministrazione Digitale ([🔗](https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2005-03-07;82!vig))
      - Defining Open in Open Data, Open Content and Open Knowledge ([🔗](https://opendefinition.org/od/2.0/it/))
      - Direttiva (UE) 2019/1024 del Parlamento europeo e del Consiglio, del 20 giugno 2019, relativa all'apertura dei dati e al riutilizzo dell'informazione del settore pubblico ([🔗](http://data.europa.eu/eli/dir/2019/1024/oj/ita))
      - FAIR Cookbook ([🔗](https://fairplus.github.io/the-fair-cookbook/content/home.html))
      - ISO/IEC 25012 | SQuaRE: requisiti della qualità di sistemi e valutazione di prodotti ([🔗](http://www.iso25000.it/styled-19/index.html))
      - Linee guida nazionali per la valorizzazione del patrimonio informativo pubblico ([🔗](https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/index.html))
