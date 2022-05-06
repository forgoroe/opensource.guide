---
lang: it
title: Aspetti legali dell'open source
description: Tutto ciò che ti sei sempre chiesto, e altro, del lato legale dell'open source.
class: legal
order: 10
image: /assets/images/cards/legal.png
related:
  - contribute
  - leadership
---

## Comprendere le implicazioni legali dell'open source

Condividere i frutti della tua attività creativa può essere un'esperienza stimolante ed appagante. Può anche comportare una mucchio di cose legali che nemmeno avevi idea di doverti preoccupare. Fortunatamente, non sei costretto a cominciare tutto da zero. Sappiamo quali siano i tuoi bisogni legali e ti possiamo essere d'aiuto. (Prima di cominciare, assicurati di leggere il nostro [disclaimer](/notices/).)

## Com'è che alle persone interessi così tanto il lato legale dell'open source?

Bella domanda! Quando ci si cimenta in lavoro creativo di qualsiasi genere (come scrittura, grafica, o codice), di default quel lavoro è sotto copyright esclusivo. Cioè, la legge presume che come autore del tuo lavoro, spetti a te decidere cosa gli altri possano farne.

Generalmente, questo significa che nessuno può utilizzare, copiare, distribuire, o modificare il tuo lavoro senza incorrere il rischio di una rimozione, shake-down, o controversia.

Tuttavia, l'Open source è una circostanze inusuale poiché l'autore si aspetta che gli altri utilizzino, modifichino, e condividano il lavoro. Ma poiché il default legale è di copyright esclusivo, hai bisogno di una licenza esplicita che affermi e conceda questi permessi.

Se non applichi una licenza open source al tuo progetto, tutti coloro che ne contribuiscono diventano altrettanto detentori del copyright del lavoro in maniera esclusiva. Ciò significa che nessuno può utilizzare, copiare, distribuire, o modificare i loro contributi -- e con "nessuno", si intende, incluso te!

Infine, il tuo progetto potrebbe avere dependencies che richiedono una licenza di cui non eri a conoscenza. La community del tuo progetto, o le polizze del tuo datore di lavoro, potrebbero altresì richiedere che il tuo progetto utilizzi specifiche licenze open source. Queste situazioni discutiamo sotto.

## I progetti GitHub pubblici sono open source?

Quando [crei un nuovo progetto](https://help.github.com/articles/creating-a-new-repository/) su GitHub, hai l'opzione di impostare la repository come **privata** o **pubblica**.

![Create repository](/assets/images/legal/repo-create-name.png)

**Rendere il tuo progetto pubblico è diverso dal concedere una licenza al tuo progetto.** I progetti pubblici sono protetti dai [termini di servizio GitHub](https://help.github.com/en/github/site-policy/github-terms-of-service#3-ownership-of-content-right-to-post-and-license-grants), i quali permettono ad altri la visione e la copia (fork) del tuo progetto, ma per quanto riguarda tutto il resto, il tuo lavoro esiste senza permessi.

Se vuoi che altri utilizzano, distribuiscano, modifichino, o contribuiscano al tuo progetto, dovrai includere una licenza open source. Per esempio, uno non può utilizzare qualsiasi parte del tuo progetto GitHub nel loro codice legalmente, seppur pubblico, a meno che tu gli dia un permesso esplicito che glielo consenta.

## Dimmi in poche parole cosa devo fare per proteggere il mio progetto.

Puoi ritenerti fortunato! Oggigiorno le licenze open source sono standardizzate e facili da utilizzare. Puoi copiare e incollare una licenza esistente direttamente nel tuo progetto.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), e [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) sono le licenze open source più popolari, ma esistono altre opzioni a tua disposizione. Puoi trovare il testo completo di queste licenze, e istruzioni su come utilizzarle presso [choosealicense.com](https://choosealicense.com/).

Quando crei un nuovo progetto su GitHub, ti verrà [richiesto di aggiungere una licenza](https://help.github.com/articles/open-source-licensing/).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/benbalter?s=180" class="pquote-avatar" alt="avatar">
  Una licenza standardizzata può servire come proxy per coloro che non hanno alcuna esperienza legale, aiutandoli a sapere precisamente cosa possono fare e cosa non possono fare con il software. A meno che sia assolutamente indispensabile, evita termini d'uso personalizzati, modificati, o non-standard, che potrebbero agire come barriera all'uso di agency code eventuale.

  _A standardized license serves as a proxy for those without legal training to know precisely what they can and can't do with the software. Unless absolutely required, avoid custom, modified, or non-standard terms, which will serve as a barrier to downstream use of the agency code._
  <p markdown="1" class="pquote-credit">
— @benbalter, ["Everything a government attorney needs to know about open source software&nbsp;licensing"](https://ben.balter.com/2014/10/08/open-source-licensing-for-government-attorneys/)
  </p>
</aside>

## Quale licenza open source è adatta al mio progetto?

Se stai cominciando da zero, è difficile che ti sbagli con la [licenza MIT](https://choosealicense.com/licenses/mit/). E' breve, molto semplice da comprendere, e permette a chiunque di fare qualsiasi cosa, purché tu tenga una copia della licenza, includendo l'avviso di copyright. Nell'occorrenza, potrai sempre rilanciare il progetto sotto una licenza diversa.

Altrimenti, scegliere la licenza appropriata al tuo progetto dipende dai tuoi obiettivi.

Con buone probabilità, il tuo progetto ha (o avrà) **dependencies**. Per esempio, se rendessi open source un progetto Node.js, utilizzerai librerie disponibili nel Node Package Manager (npm). Ciascuna di quelle librerie su cui fai affidamento avrà a sua volta la propria licenza open source. Se ciascuna licenza è "permissive" (offre permesso al pubblico di utilizzare, modificare, e condividere, senza alcuna condizione eventuale), puoi utilizzare qualsiasi licenza tu voglia. Alcune delle licenze permissive comuni includono MIT, Apache 2.0, ISC, e BSD.

Dall'altro lato, se anche una soltanto delle tue dependencies utilizzasse licenze "strong copyleft" (che offre gli stessi permessi pubblici, soggetti all'utilizzo dell'utilizzo della stessa licenza downstream), il tuo progetto sarà costretto ad utilizzare la stessa licenza. Alcune delle licenze "strong" includono GPLv2, GPLv3, e AGPLv3.

Potresti voler considerare le **community** che ti auspichi che utilizzeranno o contribuiranno al tuo progetto:

* **Vuoi che il tuo progetto venga utilizzato come dependency in altri progetti?** Probabilmente la cosa migliore è utilizzare la licenza più popolare della community pertinente. Per esempio, [MIT](https://choosealicense.com/licenses/mit/) è la licenza più popolare per [librerie npm](https://libraries.io/search?platforms=NPM).
* **Vuoi che il tuo progetto attragga larghe aziende?** Una larga azienda verosimilmente, vorrà una licenza di brevetto esplicita da tutti i contributor. In questo caso, [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) può esserti d'aiuto (e a loro).
* **Vuoi che il tuo progetto sia attraente per quei contributor che non vogliono che i loro contributi vengano utilizzati in software closed source?** [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) oppure (se inoltre non vogliono contribuire a servizi closed source) [AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) faranno al caso tuo.

La tua **azienda** potrebbe avere requisiti di licenza specifici per i propri progetti open source. Per esempio, potrebbe richiedere una licenza permissive cosicché l'azienda abbia la possibilità di utilizzare il tuo progetto nel proprio prodotto closed source. Oppure potrebbe richiedere una licenza strong copyleft e un accordo contributor aggiuntivo (vedi sotto), in modo che né la tua azienda, né altri possano utilizzare il tuo progetto in un software closed source. Oppure la tua azienda potrebbe avere certe necessità riguardo agli standard, responsabilità sociali, o trasparenza, qualsiasi delle quali potrebbe richiedere una particolare strategia di licenza. Parla con il [dipartimento legale della tua azienda](#what-does-my-companys-legal-team-need-to-know).

Quando crei un nuovo progetto su GitHub, ti viene data l'opzione di scegliere una licenza. Incluse quelle licenze menzionate sopra che renderanno il tuo progetto GitHub open source. Se volessi vedere altre opzioni, dai un'occhiata a [choosealicense.com](https://choosealicense.com) per trovare la licenza adatta al tuo progetto, anche se [non si trattasse di software](https://choosealicense.com/non-software/).

## E se volessi cambiare la licenza del mio progetto?

La maggior parte dei progetti non hanno mai bisogno di cambiare licenze. Occasionalmente però, le circostanze possono cambiare.

Per esempio, man mano che il tuo progetto cresce, le dependency o gli utenti incrementano di numero, o le strategie della tua azienda cambiano, potrebbe sorgere il bisogno di una licenza diversa. Inoltre, se hai trascurato la licenza del tuo progetto dall'inizio, aggiungere una licenza equivale a cambiarla. Ci sono tre cose fondamentali da considerare quando aggiungi o cambi la licenza del tuo progetto:

**E' complesso.** Determinare la compatibilità delle licenze e chi detiene il copyright può divenire molto complesso e disorientante velocemente. Il passaggio ad una licenza nuova compatibile per nuovi rilasci e contributi è differente dal cambiare la licenza di tutti i contributi esistenti. Coinvolgi il tuo team legale al primo indizio di qualsiasi desiderio di cambiare la licenza. Anche se disponi di o puoi ottenere un permesso per un cambio di licenza da parte dei titolari del copyright di progetto, considera l'impatto che il cambio può avere sugli utenti del progetto e altri contributor. Considera un cambio di licenza come un "evento di governance" per il tuo progetto che andrà più liscio con una consultazione e una linea chiara di comunicazione con gli stakeholder di progetto. Considerati tutti questi aspetti, la scelta di una licenza appropriata fin dall'inizio è maggiormente importante!

**La licenza del tuo progetto esistente.** Se la licenza esistente del tuo progetto è compatibile con la nuova, puoi semplicemente cominciare ad utilizzare la nuova. Questo è perché se la licenza A è compatibile con la licenza B, i termini della licenza A saranno conformi con quelli della licenza B (ma non necessariamente vice versa). Quindi se stai attualmente utilizzando una licenza permissive (come per esempio, MIT), potresti passare ad una licenza con maggiori condizioni, purché tu ritenga una copia della licenza MIT e qualsiasi altro avviso di copyright associato (per esempio, continuando ad attenerti alle condizioni minime della licenza MIT). Ma se la tua licenza non è permissive (per esempio, copyleft, o non hai una licenza) e non sei il solo titolare del copyright, non puoi semplicemente cambiare la licenza di progetto ad una licenza MIT. Essenzialmente, con una licenza permissive i detentori dei copyright hanno dato il loro permesso anticipato per il cambio delle licenze.

**I titolari del copyright di progetto correnti.** Se sei il solo contributor, tu o la tua azienda siete gli unici titolari dei copyright del progetto. Puoi aggiungere o adottare qualsiasi nuova licenza che tu o la tua azienda vogliate. Diversamente ci potrebbero esser altri detentori dei copyright con cui avrai bisogno di accordarti per cambiare licenza. Chi sono? Per cominciare, coloro che hanno commit nel tuo progetto. Ma in alcuni casi il copyright apparterrà ai datori di lavoro degli impiegati. In alcuni casi le persone avranno apportato contribuzioni minime, ma non c'è una regola ferrea che affermi che i contributi sotto un numero di linee di codice non siano soggetti a copyright. Che fare? Dipende. Per un progetto relativamente piccolo e recente, potrebbe essere fattibile trovare un accordo con tutti i contributor esistenti affinché si cambi la licenza utilizzando una issue o pull request. Per progetti più grandi e longevi, potresti dover andare alla ricerca di parecchi contributor e perfino i loro eredi. Mozilla ha impiegato anni (2001-2006) per cambiare licenze per Firefox, Thunderbird, e altro software.

In alternativa, puoi far sì che i contributor si mettano d'accordo anticipatamente (tramite un accordo aggiuntivo -- vedi sotto) rispetto a certe licenze sotto certe condizioni particolari, oltre a quelle permesse dalla tua licenza open source esistente. Questo diminuisce leggermente la complessità associata con i cambi di licenza. Avrai bisogno di aiuto maggiore da parte dei tuoi avvocati fin dall'inizio, e nell'eseguire il cambio di licenza eventuale, avrai comunque bisogno di mantenere una comunicazione chiara con gli stakeholder del tuo progetto.

## Il mio progetto ha bisogno di un contributor agreement aggiuntivo?

Probabilmente no. Per la maggior parte dei progetti open source, una licenza open source implicitamente funge sia da licenza inbound (dai contributor) che outbound (verso altri contributor e utenti). Se il tuo progetto è su GitHub, i termini di servizio GitHub rendono questo "inbound=outbound" una regola [esplicita predefinita](https://help.github.com/en/github/site-policy/github-terms-of-service#6-contributions-under-repository-license).

Un contributo agreement aggiuntivo -- spesso noto come un Contributor License Agreement (CLA) -- può creare lavoro amministrativo per i maintainer del progetto. Quanto lavoro un accordo aggiunge dipende dall'implementazione e dal progetto. Un semplice accordo potrebbe richiedere che i contributor confermino, con un click, di avere i diritti necessari a contribuire secondo la licenza open source del progetto. Un accordo più complesso potrebbe richiedere una revisione legale e l'approvazione dai datori di lavoro dei contributor.

Inoltre, aggiungendo "documenti" che alcuni credono siano inutili, difficili da comprendere, o ingiusti (quando i destinatari dell'accordo ricevono più diritti rispetto a contributor o del pubblico tramite la licenza open source del progetto), un contributor agreement aggiuntivo potrebbe venir percepito come scortese nei confronti della community del progetto.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/bcantrill?s=180" class="pquote-avatar" alt="avatar">

    Abbiamo eliminato il CLA da Node.js. Così facendo abbiamo bassato la barriera d'ingresso per contributor Node.js e ampliato il numero di contributor.

    _We have eliminated the CLA for Node.js. Doing this lowers the barrier to entry for Node.js contributors thereby broadening the contributor base._

  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.joyent.com/blog/broadening-node-js-contributions)
  </p>
</aside>

Alcune delle situazioni in cui potresti voler considerare un contributor agreement aggiuntivo per il tuo progetto includono:

* I tuoi avvocati vogliono che tutti i contributor accettino espressamente (_firmino_, online o offline) i termini di contributo, probabilmente perché ritengono che la licenza da sola non basti (seppur non sia così!). Se questo è l'unico timore, un contributor agreement che confermi la licenza del progetto come open source, dovrebbe bastare. La [licenza di contributo individuale jQuery](https://contribute.jquery.org/CLA/) è un buon esempio di contributor agreement  "leggero" aggiuntivo.
* Tu o i tuoi avvocati volete che gli sviluppatori rendano tutti i commit visibilmente autorizzati. Per ottenere ciò, molti progetti utilizzano un [Developer Certificate of Origin](https://developercertificate.org/). Per esempio, la community Node.js [utilizza](https://github.com/nodejs/node/blob/HEAD/CONTRIBUTING.md) il DCO [al posto](https://nodejs.org/en/blog/uncategorized/notes-from-the-road/#easier-contribution) della CLA precedente. Una semplice opzione che automatizzi l'applicazione del DCO sul tuo repository è il [DCO Probot](https://github.com/probot/dco).
* Il tuo progetto utilizza una licenza open source che non include una concessione di brevetto esplicita (come la MIT), e hai bisogno di una concessione di brevetto da parte di tutti i contributor, alcuni dei quali potrebbero lavorare per compagnie con grandi portfolio che potrebbero venire utilizzati per prendere di mira te o i contributor e utenti del progetto. La licenza [Apache Individual Contributor License Agreement](https://www.apache.org/licenses/icla.pdf) è un contributor agreement comune aggiuntivo che ha una concessione di brevetto che rispecchia quello presente nella licenza Apache 2.0.
* Il tuo progetto è sotto una licenza copyleft, ma desideri anche distribuire una versione brevettata del progetto. Avrai bisogno che tutti i contributor assegnino il copyright o a te oppure offrano a te (ma non al pubblico) una licenza permissive. Il [MongoDB Contributor Agreement](https://www.mongodb.com/legal/contributor-agreement) è un esempio di questo tipo di agreement.
* Pensi che il tuo progetto possa aver bisogno di cambiare licenza lungo il corso della sua esistenza e vuoi che i contributor siano d'accordo anzitempo.

Se hai bisogno di un contributor agreement aggiuntivo con il tuo progetto, considera l'utilizzo di una integration come la [CLA assistant](https://github.com/cla-assistant/cla-assistant) per minimizzare le distrazioni dei contributor.

## Cos'ha bisogno di sapere il mio team legale?

Se stai per lanciare un progetto open source in qualità di impiegato, prima di tutto, è opportuno che il tuo team legale sappia che stai rendendo un progetto open source.

Comunque sia, valuta di farglielo sapere anche se si trattasse di un progetto personale. E' probabile che tu abbia un "employee IP agreement" con la tua azienda che offre loro del controllo sui tuoi progetti, specialmente se non sono legati agli affari dell'azienda, o se stessi utilizzando risorse aziendali per sviluppare il progetto. La tua azienda _dovrebbe_ permettertelo facilmente, e magari l'ho ha già fatto tramite un accordo IP employee-friendly o polizza aziendale. Se così non fosse, puoi trattare (per esempio, spiegando che secondo te il tuo progetto è d'aiuto all'apprendimento e allo sviluppo professionale dell'azienda), oppure evita di lavorarci finché non trovi un'azienda migliore.

**Se stai rendendo un progetto dell'azienda open source,** faglielo assolutamente sapere. Il tuo team legale probabilmente ha già polizze riguardo quale licenza open source utilizzare basata sulle esigenze d'affari dell'azienda, e considerazioni già fatte sulle licenze più conformi alle varie licenze delle dependency del progetto. Se così non fosse, siete entrambi fortunati! Il tuo team legale dovrebbe essere entusiasta di lavorare con te per capire il da farsi. Alcune cose su cui riflettere:

* **Materiale di terze parti:** Il tuo progetto ha dependency create da altri o che includono codice altrui? Se queste sono open source, dovrai attenerti alle licenze di quelle stesse dependency o materiali. Questo comincia con la scelta di una licenza che calzi con le licenze open source dei materiali di terze parti (vedi sopra). Se il tuo progetto modifica o distribuisce materiale open source di terze parti, il tuo team legale vorrà altrettanto sapere che stai rispettando le condizioni delle licenze open source delle terze parti, come per esempio, la trattenuta degli avvisi di copyright. Se il tuo progetto utilizza codice altrui che non dispone di una licenza open source, dovrai probabilmente chiedere a maintainer terzi di [aggiungere una licenza open source](https://choosealicense.com/no-license/#for-users), e se non riuscissi, smettere di utilizzare il loro codice nel tuo progetto.

* **Scambia segreti:** Considera se c'è qualcosa nel progetto che l'azienda non vuole rendere disponibile al pubblico. Se così fosse, potresti rendere open source il resto del tuo progetto, dopo aver estratto il materiale che vuoi tenere privato.

* **Brevetti:** La tua azienda sta richiedendo un brevetto, e rendere il tuo progetto open source costituirebbe [public disclosure](https://en.wikipedia.org/wiki/Public_disclosure)? Sfortunatamente, potrebbe esserti richiesto di attendere (o magari l'azienda rivaluterà il proprio giudizio nel richiedere il brevetto). Se ti aspetti contributi progetto da parte di impiegati ed aziende con grandi portfolio, il tuo team legale potrebbe voler utilizzare una concessione di brevetto dai contributor (come Apache 2.0 oppure GPLv3), oppure un contributor agreement aggiuntivo (vedi sopra).

* **Marchi registrati:** Verifica due volte che il nome del tuo progetto [non vada in conflitto con marchi registrati esistenti](../starting-a-project/#avoiding-name-conflicts). Se utilizzassi marchi registrati della tua stessa azienda nel progetto, controlla che non causino conflitti. [FOSSmarks](http://fossmarks.org/) è una guida alla comprensione dei marchi registrati per progetti open source gratuiti.

* **Privacy:** Il tuo progetto colleziona dati sugli utenti? Invia dati ai server d'azienda? Il tuo team legale può aiutarti ad attenerti alle polizze e normative esterne aziendali. Se stai lanciando il tuo primo progetto aziendale open source, ciò menzionato sopra dovrebbe essere più che sufficiente per farcela (ma non preoccuparti, la maggior parte dei progetti non dovrebbero suscitare preoccupazioni notevoli).

Nel lungo termine, il tuo team legale può fare di più per assicurarsi di avere un ritorno maggiore nel suo impegno nell'open source, e rimanere sicuro:

* **Polizze di contributo dei dipendenti:** Considera lo sviluppo di una polizza aziendale che precisi come i tuoi dipendenti contribuiscono su progetti open source. Una polizza chiara ridurrà la confusione tra i dipendenti e aumenterà il numero di contributi verso progetti open source utili all'azienda, indipendentemente che siano frutto di tempo impiegato a lavoro o nel loro tempo libero. Un buon esempio è la polizza [Model IP and Open Source Contribution Policy](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/) di Rackspace.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/vanl?s=180" class="pquote-avatar" alt="avatar">

  Rilasciare l'IP associato con una patch incrementa le conoscenze del dipendente e la sua reputazione. Dimostra che l'azienda è dedicata alla crescita di quell'impiegato oltre che a creare un senso di responsabilità ed autonomia. Tutti questi benefici portano a maggiori energie per l'impiegato e una maggiore probabilità che gli impiegati rimangano.

  _Letting out the IP associated with a patch builds the employee's knowledge base and reputation. It shows that the company is invested in the development of that employee and creates a sense of empowerment and autonomy. All of these benefits also lead to higher morale and better employee retention._

  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

* **Cosa lanciare:** [(Quasi) Tutto?](http://tom.preston-werner.com/2011/11/22/open-source-everything.html) Se il tuo team legale comprende ed è investito nella strategia open source aziendale, sarà in una posizione migliore per sostenere i tuoi sforzi piuttosto che ostacolarli.

* **Conformità:** Anche se la tua azienda non rilascia alcun progetto open source, utilizza comunque open source software altrui. Una buona [consapevolezza e una buona attenzione rispetto alle procedure][Awareness and process](https://www.linuxfoundation.org/blog/2015/06/why-companies-that-use-open-source-need-a-compliance-program/) possono prevenire mal di testa, ritardi, e cause legali.

<aside markdown="1" class="pquote">

  Un'organizzazione deve avere in vigore una licenza e una strategia di conformità che si adattino ad entrambe le categorie \["permissive" che "copyleft"\]. Questo comincia con la conservazione di tutti quei record di termini di licenza applicabili al software open source che stai utilizzando - sottocomponenti e dependency incluse.

  _Organizations must have a license and compliance strategy in place that fits both \["permissive" and "copyleft"\] categories. This begins with keeping a record of the licensing terms that apply to the open source software you’re using — including subcomponents and dependencies._

  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Open Source Software: Compliance Basics And Best Practices"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

* **Brevetti:** La tua azienda potrebbe unirsi all'[Open Invention Network](https://www.openinventionnetwork.com/), un gruppo comune defensive patent per la protezione di membri di progetti open source principali, oppure esplorare [licenze di brevetto alternative](https://www.eff.org/document/hacking-patent-system-2016).

* **Amministrazione:** Specialmente se e quando è opportuno disporre un progetto ad un'[entità legale al di fuori dell'azienda](../leadership-and-governance/#do-i-need-a-legal-entity-to-support-my-project).
