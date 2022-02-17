---
hide:
  - toc
title: Etica dei dati
---

# Etica dei dati

*di [Valentina Bazzarin](https://twitter.com/VBazzarin), [Diletta Huyskes](https://twitter.com/dilettahuyskes_), [Paola Chiara Masuzzo](https://twitter.com/pcmasuzzo)*

Fare in modo che i dati e quello che producono siano etici va ben oltre la conformità: **è un atto di coraggio, e un po’, forse, anche di ribellione**.

La *data science*^[ℹ️](glossario.md#data-science)^ ha evidenti impatti sulla società e sulla vita pubblica. Per questo le sfide legate all’etica devono essere tenute in considerazione nel dibattito e soprattutto nelle politiche e nel governo dei dati e delle infrastrutture digitali e tecnologiche.

L’[etica dei dati](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2907744), come campo specializzato dell’etica tecnologica, studia e valuta le fasi di **generazione**, **registrazione**, **cura**, **elaborazione**, **condivisione** e **utilizzo** dei dati e delle pratiche corrispondenti, comprese le interazioni tra hardware, software e i dati stessi.

In ambito economico sono stati individuati 5 principi da osservare nelle organizzazioni e che possono essere mutuati dalle comunità o dai soggetti che operano nell’ecosistema dei dati, come decisori, come produttori o come fruitori.

1. ***Governance*** del dato: è necessario che sia sempre identificabile e che l’uso ne sia consentito.

2. **Trasparenza**: è un esercizio doveroso per le pubbliche amministrazioni e indispensabile quando, per esempio, si redige una *policy* o i dati vengono utilizzati all’interno di algoritmi.

3. ***Privacy***: quando trattiamo dati personali o dati particolari (biometrici o sensibili) è necessario tutelare la dignità e i diritti delle persone coinvolte, individuare i responsabili e controllare la conformità di ogni trattamento al GDPR.

4. **Intenzioni / obiettivi**: Le intenzioni contano e la minimizzazione dei dati raccolti sono un requisito, quindi prima di iniziare una raccolta o un trattamento è indispensabile chiedersi quali sono gli obiettivi e individuare quali siano i dati necessari al loro raggiungimento.

5. ***Outcomes*** (risultati/prodotti): se è vero che le intenzioni contano, l’impatto di ogni attività verrà misurato principalmente sui risultati o sui prodotti del trattamento. Per esempio, è sempre necessario valutare se il risultato di un’analisi o il grafico che lo descrive non contenga dei pregiudizi oppure non possa essere utilizzato per escludere o discriminare dei gruppi o delle persone.

Questi 5 principi guidano ogni passo di un tipico *data science workflow*. Bisogna, in particolar modo, mettere insieme procedure e azioni collettive affinché tutto quello che viene prodotto mediante l’utilizzo di dati pubblici contribuisca alla lotta contro discriminazioni e ingiustizie e alla costruzione di un tessuto sociale più equo: insomma, che **risolva problemi anziché crearne di nuovi**.

Le fasi di un processo di *data science* che dovrebbero essere sempre guidate dai 5 principi possono essere riassunte come segue:

  - La **collezione** di dati, prima, la **selezione** delle sorgenti di dati, dopo, e l’eventuale **integrazione** con fonti esterne, devono essere tutte guidate dalla **trasparenza**; fondamentali a tal scopo sono: spiegazione dei metodi utilizzati, chiara provenienza dei dati tramite metadati descrittivi, comunicazione onesta di limitazioni, tecniche e non.

  - L’**estrazione delle informazioni** dai dati, che si può ottenere attraverso:

      - la **selezione** dei dati (per un certo scopo): garantire la diversità e l’equità dei campioni e delle dimensioni selezionati non può mai essere un *afterthought*;

      - l’**aggregazione** dei dati tramite la semplice interrogazione degli stessi: tipiche *query* aggregate tendono a nascondere alcune dimensioni/tendenze (si pensi al [paradosso Simpson](https://it.wikipedia.org/wiki/Paradosso_di_Simpson)) e quindi a fornire informazioni distorte e rafforzare discriminazioni;

      - **analisi** dei dati attraverso modelli statistici, algoritmi di *machine learning*^[ℹ️](glossario.md#machine-learning)^ (modelli addestrati o meno) e di *deep learning*^[ℹ️](glossario.md#deep-learning)^; è particolarmente importante valutare l’impatto che tecniche analitiche hanno sulla formulazione degli *outcomes* finali, specialmente quando gli algoritmi sono opachi (si pensi al *deep learning*, o più semplicemente ad analisi effettuate con codice non accessibile, non *open source*) e quando hanno potere decisionale sulla vita delle persone;

      - **visualizzazione** dei dati (prima e/o dopo le analisi); il pensiero etico non riguarda solo le intenzioni ma anche le conseguenze che possono derivare dalla presentazione finale dei dati attraverso dashboard, grafici, report, storie. Generare valore attraverso una storia informata dai dati è un obiettivo che non può mai prescindere dallo sforzo continuo di creare narrazioni della realtà più giuste, eque, inclusive.

Qualsiasi progetto che richieda, utilizzi o raccolga una grande quantità di dati - specie se nel settore pubblico - dovrebbe preoccuparsi della loro **qualità**, **coerenza** e **affidabilità** durante l’intero ciclo di vita del progetto, attraverso un **monitoraggio** continuo e analisi del rischio iterative. A causa della natura mutevole di molti tipi di dati, un simile approccio è indispensabile per riadattare il progetto in base agli impatti osservati. In quest’ottica, è fondamentale che questi progetti siano sensibili al contesto applicativo, prevedendo ad esempio un **coinvolgimento attivo delle comunità e delle persone interessate**.

Adottare un approccio etico all’utilizzo dei dati significa impiegarli per generare impatti positivi: come dicevamo prima, è un approccio che va ben oltre la conformità.
