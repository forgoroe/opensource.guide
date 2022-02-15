---
lang: it
title: Creare community accoglienti
description: Creare una community che incoraggia le persone ad utilizzare, contribuire a, e venerare il tuo progetto.
class: building
order: 4
image: /assets/images/cards/building.png
related:
  - best-practices
  - coc
---

## Prepara il tuo progetto al successo

Hai avviato il tuo progetto, si sta spargendo la voce, e la gente lo sta visitando. Ottimo! Ora, come fai in modo che rimangano nei paraggi?

Una community accogliente è un investimento per il futuro del tuo progetto e la tua reputazione. Se il tuo progetto ha appena cominciato ad avere contributi, comincia con l'offrire ai primi contributor una buona esperienza, e rendi appetibile il loro ritorno.

### Falli sentire benvenuti

Un modo per riflettere sulla community del tuo progetto è attraverso ciò che @MikeMcQuaid chiama l'[imbuto dei contributor (contributor funnel)](https://mikemcquaid.com/2018/08/14/the-open-source-contributor-funnel-why-people-dont-contribute-to-your-open-source-project/):

![Contributor funnel](/assets/images/building-community/contributor_funnel_mikemcquaid.png)

Man mano che costruisci la tua community, considera come qualcuno all'apice dell'imbuto (un potenziale utente) possa teoricamente raggiungere il fondo (diventando un maintainer attivo). Il tuo obiettivo è ridurre la frizione dell'esperienza del contributore ad ogni stadio. Quando la gente vince facile, è incentivata a fare di più.

Comincia con la tua documentazione:

* **Rendi l'utilizzo del tuo progetto semplice** [Un amichevole README](../starting-a-project/#writing-a-readme) ed esempi di codice chiari renderanno più semplice l'inizio del lavoro da parte di coloro che si ritrovano sul tuo progetto.
* **Spiega in modo chiaro come contribuire**, utilizzando [il tuo file CONTRIBUTING](../starting-a-project/#writing-your-contributing-guidelines) e mantenendo le tue issue aggiornate.
* **Buone prime issue**: Per aiutare nuovi contributor ad iniziare, considera esplicitamente [di contrassegnare quelle issue semplici e adatte a principianti come tali](https://help.github.com/en/articles/helping-new-contributors-find-your-project-with-labels). Github si prenderà cura di rendere quelle issue visibili in altri posti sulla piattaforma, incrementando i contributi utili, e riducendo la frizione creata da utenti che affrontano issue troppo difficili al loro livello.

[GitHub's 2017 Open Source Survey](http://opensourcesurvey.org/2017/) mostra che documentazione confusa o incompleta è il più grande problema per utenti open source. Una buona documentazione invita le persone a interagire con il tuo progetto. Prima o poi, qualcuno invierà una issue o pull request. Usa queste interazioni come opportunità di movimento verso il fondo dell'imbuto.

* **Quando qualcuno si ritrova sul tuo progetto, ringraziali per il loro interesse!** Occorre soltanto un'esperienza negativa per far sì che qualcuno non voglia ritornare.
* **Sii reattivo.** Se non rispondi alla loro issue per un mese, ci sono buon probabilità che abbiano già dimenticato il tuo progetto.
* **Mantieni una mente aperta rispetto a quali contributi accetti** Molti contributor cominciano con un piccolo bug report o una piccola soluzione. Ci sono [molti modi di contribuire](../how-to-contribute/#what-it-means-to-contribute) ad un progetto. Lascia che le persone aiutino come vogliono aiutare.
* **Se c'è un contributo con cui non sei d'accordo,** ringraziali per la loro idea e [spiega perchè](../best-practices/#learning-to-say-no) non è adatto allo scope del progetto, fornendo link alla documentazione relativa se disponibile.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mikeal?s=180" class="pquote-avatar" alt="avatar">

  Contribuire all'open source talvolta è più facile per qualcuno che per altri. C'è molta paura di essere rimproverati per non aver fatto qualcosa in moro corretto o non adatto. (...) Dando uno spazio dove i contributor possono contribuire anche con minori conoscenze technice (documentazione, contentuti web markdown, ecc.) puoi ridurre in maniera drastica quei timori.

  _Contributing to open source is easier for some than others. There's a lot of fear of being yelled at for not doing something right or just not fitting in. (...) By giving contributors a place to contribute with very low technical proficiency (documentation, web content markdown, etc) you can greatly reduce those concerns._
  <p markdown="1" class="pquote-credit">
— @mikeal, ["Growing a contributor base in modern open source"](https://opensource.com/life/16/5/growing-contributor-base-modern-open-source)
  </p>
</aside>

La maggior parte dei contributor open source sono "contributor casuali": persone che contribuiscono al progetto soltanto occasionalmente. Un contributore casuale potrebbe non avere il tempo di essere aggiornato perfettamente con il tuo progetto. Per questo, è il tuo compito di rendere facile la loro contribuzione.

Incoraggiare altri contributor è anche un investimento per te stesso. Quando responsabilizzi i tuoi più grandi fan a eseguire il lavoro per cui sono più appassionati, c'è molta meno pressione di dover fare tutto da solo.

### Documenta tutto

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/janl?s=180" class="pquote-avatar" alt="avatar">

  Sei mai stato ad un evento (tech) dove non conoscevi nessuno, ma tutti gli altri sembravano fossero in gruppi a chiacchierare come vecchi amici? (...) Ora immagina che vuoi contribuire ad progetto open source, ma non vedi perchè o come questo sta succedendo.

  _Have you ever been to a (tech-) event where you didn't know anyone, but everyone else seemed to stand in groups and chat like old friends? (...) Now imagine you want to contribute to an open source project, but you don't see why or how this is happening._

  <p markdown="1" class="pquote-credit">
— @janl, ["Sustainable Open Source"](https://web.archive.org/web/20200723213552/https://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

Quando incominci un nuovo progetto, tenere il tuo lavoro privato potrebbe sembrare naturale. Ma progetti open source prosperano quando documenti il tuo processo pubblicamente.

Quando annoti il tuo processo, più persone possono rendersi partecipi ad ogni passo del tuo cammino. Potresti ricevere aiuto su qualcosa che nemmeno sapevi di aver bisogno di ricevere.

Annotare significa più di una semplice trasposizione della documentazione puramente tecnica. Ogni volta che senti l'impulso di scrivere qualcosa o di discuterlo privatamente, domandati se puoi renderlo pubblico.

Sii trasparente rispetto alla tua roadmap di progetto, i tipi di contributi che cerchi, come i contributi sono revisionati, o perchè hai preso certe decisioni.

Se noti che diversi hanno lo stesso problema, documenta le tue risposte nel README.

Quando si tratta di incontri, considera la pubblicazione delle tue note o cose da ricordare in una issue pertinente. Il feedback che riceverai tramite questo livello di trasparenza potrebbe sorprenderti.

Documentare tutto comprende anche il lavoro che fai. Se stai lavorando su un aggiornamento considerevole per il tuo progetto, mettilo in una pull request e marcalo come work in progress (WIP). Così facendo gli altri potranno sentirsi al più presto parte del processo.

### Sii reattivo

Mentre [promuovi il tuo progetto](../finding-users), riceverai feedback da diverse persone. Potrebbero avere domande su come funzionano le cose, o potrebbero aver bisogno di aiuto su come cominciare.

Cerca di rimanere reattivo quando qualcuno invia una issue, una pull request, o fa domande sul tuo progetto. Quando rispondi in fretta, li farai sentire parte di un dialogo e saranno più entusiaste a partecipare.

Anche se non riesci a controllare la request immediatamente, prendendo atto e rendendo noto presto di averla ricevuta fa in modo che il livello di coinvolgimento aumenti. Ecco come @tdreyno ha risposto ad una pull request su [Middleman](https://github.com/middleman/middleman/pull/1466):

![Middleman pull request](/assets/images/building-community/middleman_pr.png)

[Uno studio condotto da Mozilla](https://docs.google.com/presentation/d/1hsJLv1ieSqtXBzd5YZusY-mB8e1VJzaeOmh8Q4VeMio/edit#slide=id.g43d857af8_0177) ha trovato che contributor che avevano ricevuto una revisione entro le 48 ore, avevano avuto una percentuale di rientro maggiore e contribuzioni ripetute.

Conversazioni relative al tuo progetto potrebbero anche avvenire in altri posti online come Stack Overflow, Twitter, o Reddit. Puoi configurare le tue notifiche su alcuni di questi siti per essere avvertito quando qualcuno menziona il tuo progetto.

### Offri alla tua community un posto dove radunarsi

Ci sono due ragioni per offrire alla tua community un posto dove possono ritrovarsi.

La prima ragione è per loro. Aiuta a far sì che ognuno si possa conoscere. Persone aventi interessi in comune vorrano inevitabilmente un posto dove possono parlarne. E quando la comunicazione è pubblica ed accessibile, chiunque può leggere archivi passati per aggiornarsi e partecipare.

La seconda ragione è per te. Se non offri loro un posto pubblico dove possono parlare del tuo progetto, ti contatteranno direttamente. All'inizio, rispondere a messaggi privati "solo questa volta" potrebbe sembrare abbastanza semplice. Col passare del tempo, specialmente se il tuo progetto diviene popolare, ti sentirai esausto. Resisti la tentazione di comunicare del tuo progetto in privato. Cerca invece di indirizzali verso un canale pubblico designato.

La comunicazione pubblica può consistere in semplici accorgimenti come quello di incoraggiare le persone ad aprire una issue invece di mandarti una email direttamente o commentare sul tuo blog. Potresti inoltre configurare una mailing list o creare un account Twitter, Slack o un canale IRC predisposto alla discussione del tuo progetto. O tutto quanto sopra menzionato!

[Kubernetes kops](https://github.com/kubernetes/kops#getting-involved) alloca ore d'ufficio ogni due settimane per aiutare membri della community:

> Kops inoltre, alloca un certo orario ogni due settimane per offrire assistanza e orientamento alla community. I maintainer di Kops hanno messo da parte tempo specifico da dedicare al lavoro con nuovi arrivati, aiutando con PRs, e discutendo nuove feature.
>
> Kops also has time set aside every other week to offer help and guidance to the community. Kops maintainers have agreed to set aside time specifically dedicated to working with newcomers, helping with PRs, and discussing new features.

Eccezioni di rilievo alla comunicazione pubblica sono: 1) problemi di sicurezza e 2) violazioni ai codici di condotta sensibili. Dovresti sempre avere modalità di report separate per gestire queste problematiche privatamente. Se non vuoi utilizzare la tua email personale, configura un indirizzo email dedicato.

## La crescita della tua community

Le community sono estremamente potenti. Tale potere può essere una benedizione così come una maledizione, a seconda di come viene esercitato. Man mano che la tua community di progetto cresce, ci sono modi per facilitare il suo divenire una forza costruttiva, anzichè una distruttiva.

### Non tollerare i malintenzionati

Qualunque progetto popolare attrarrà inevitabilmente persone che vogliono danneggiare, piuttosto che aiutare, la tua community. Potrebbero cominciare discussioni inutili, disquisire su feature insignificanti, o intimidire altre persone.  

Adotta il più possibile una polizza tolleranza zero rispetto a questo tipo di persone. Se non controllate, persone negative di questo genere creeranno esperienze sgradevoli che potrebbero persino indurre altri membri ad abbandonare la community.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/okdistribute?s=180" class="pquote-avatar" alt="avatar">

  La verità è che avere una community incoraggiante e solidale è essenziale. Non riuscirei mai a fare questo lavoro senza l'aiuto dei miei colleghi, amichevoli stranieri su internet, e canali IRC loquaci. (...) Non accontentarti di meno. Non accontentarti degli stronzi.

  _The truth is that having a supportive community is key. I'd never be able to do this work without the help of my colleagues, friendly internet strangers, and chatty IRC channels. (...) Don't settle for less. Don't settle for assholes._

  <p markdown="1" class="pquote-credit">
— @okdistribute, ["How to Run a FOSS Project"](https://okdistribute.xyz/post/okf-de)
  </p>
</aside>

Discussioni regolari su aspetti banali del progetto distraggono gli altri, te stesso, e impedisce che ci si possa concentrare su mansioni importanti. Potrebbe succedere che nuove persone appena giunte sul tuo progetto vedano queste conversazioni e decidino di non partecipare.

Quando noti comportamenti negativi attorno al tuo progetto, rendilo noto pubblicamente. Spiega, in un tono cortese ma fermo, come mai il loro comportamento non è accettabile. Se il problema persiste, potrebbe essere il caso di [richiedergli di andarsene](../code-of-conduct/#enforcing-your-code-of-conduct). Il tuo [codice di condotta](../code-of-conduct/) può essere una guida costruttiva per questo tipo di conversazioni.

### Incontra i contributor dove sono

Più la tua community cresce, più importante diventa avere buona documentazione. contributor casuali, i quali potrebbero non essere ancora familiari con il tuo progretto, leggeranno la tua documentazione per farsi il quadro del progetto e della situazione velocemente.

Nel tuo file CONTRIBUTING, spiega esplicitamente come nuovi contributor possono iniziare. A questo fine potresti anche creare una sezione dedicata. [Django](https://github.com/django/django), per esempio, ha una pagina landing speciale per dare il benvenuto a nuovi contributor.

![Django new contributors page](/assets/images/building-community/django_new_contributors.png)

Nella tua coda di issue, marca bug come adatti a diversi tipi di contributor: per esempio, [_"first timers only"_](https://kentcdodds.com/blog/first-timers-only), _"good first issue"_, oppure _"documentation"_. [Queste "labels"](https://github.com/librariesio/libraries.io/blob/6afea1a3354aef4672d9b3a9fc4cc308d60020c8/app/models/github_issue.rb#L8-L14) rendono semplice e veloce, per coloro che sono nuovi al tuo progetto, la rilevazione di issue e il loro inizio.

Infine, usa la tua documentazione per far sentire tutti benvenuti ad ogni passo.

Non interagirai con la maggior parte delle persone che atterreranno sul tuo progetto. Ci potrebbero essere contributi che nemmeno riceverai perchè qualcuno potrebbe essersi sentito impaurito o non sapeva dove cominciare. Bastano poche parole gentili e incoraggianti a far sì che qualcuno non abbandoni il tuo progetto frustrati.


Per esempio, ecco come [Rubinius](https://github.com/rubinius/rubinius/) comincia [la sua guida contributing](https://github.com/rubinius/rubinius/blob/HEAD/.github/contributing.md):

>Volevamo cominciare col ringraziarti per aver scelto di utilizzare Rubinius. Questo progetto è un lavoro d'amore, e apprezziamo tutti gli utenti che trovano bug, migliorano i tempi di esecuzione, e aiutano con la documentazione. Ogni contributo è importante, quindi grazie per la tua partecipazione. Detto ciò, ecco alcune linee guida che ti chiediamo di seguire nell'interesse di una risoluzione positiva alla tua issue.
>
>We want to start off by saying thank you for using Rubinius. This project is a labor of love, and we appreciate all of the users that catch bugs, make performance improvements, and help with documentation. Every contribution is meaningful, so thank you for participating. That being said, here are a few guidelines that we ask you to follow so we can successfully address your issue.

### Condividi un senso di proprietà sul progetto

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/sagesharp?s=180" class="pquote-avatar" alt="avatar">

  I tuoi leader avranno opinioni diverse, come è consono che sia in community sane! Ciò nonostante, occorre prendere certi accorgimenti per assicurarsi che le voci più rumorose non vincano sempre su quelle meno prominenti. In modo da poter essere anche quest'ultime sentite.

  _Your leaders will have different opinions, as all healthy communities should! However, you need to take steps to ensure the loudest voice doesn't always win by tiring people out, and that less prominent and minority voices are heard._

  <p markdown="1" class="pquote-credit">
— @sagesharp, ["What makes a good community?"](https://sage.thesharps.us/2015/10/06/what-makes-a-good-community/)
  </p>
</aside>

Le persone sono più entusiaste a contribuire quando hanno la sensazione che il progetto sia loro. Questo non significa che tu debba rinunciare alla tua visione di progetto o accetare contributi che non vuoi. Ma dando maggiore e maggiore credito per lavoro altrui, man mano incrementerai la possibilità che i tuoi contributor rimangano nei paraggi.

Vedi se riesci a trovare modi per condividere la proprietà del tuo progetto il maggiormente possibile. Ecco alcune idee:

* **Non risolvere semplici bug (non critici).** Usali come opportunità per la recluta di nuovi contributor, o per fare da mentore a chi vuole contribuire. Inizialmente potrebbe sembrare non naturale, ma col passare del tempo ne varrà l'investimento. Per esempio, @michaeljoseph ha richiesto a contributor di inviare una pull request su una issue [Cookiecutter](https://github.com/audreyr/cookiecutter), piuttosto che risolverla da sè.

![Cookiecutter issue](/assets/images/building-community/cookiecutter_submit_pr.png)

* **Comincia un file CONTRIBUTORS o AUTHORS nel tuo progetto** che elenchi tutti coloro che hanno contribuito al progetto, come fa [Sinatra](https://github.com/sinatra/sinatra/blob/HEAD/AUTHORS.md) does.

* **Se hai una community numerosa, **invia una newsletter o un blog post** ringraziando i contributori. [This Week in Rust](https://this-week-in-rust.org/) di Rust e [Shoutouts](http://hood.ie/blog/shoutouts-week-24.html) di Hoodie sono due buoni esempi.

* **Dai ad ogni contributor commit access.** @felixge ha riscontrato che questo rendeva le persone [più entusiaste di pulire le loro patch](https://felixge.de/2013/03/11/the-pull-request-hack.html), oltrechè incontrare nuovi maintainer per progetti su cui aveva smesso di lavorare da tempo.

* Se il tuo progetto è su GitHub, **sposta il tuo progetto dal tuo account personale ad una [Organization](https://help.github.com/articles/creating-a-new-organization-account/)** e aggiungi almeno un admin di riserva. Organisation rende più semplice la collaborazione con collaboratori esterni.

La realtà è che [la maggior parte dei progetti hanno solo] uno o due maintainer che fanno la maggior parte del lavoro. Più grande è il tuo progetto, più grande sarà la tua community, più facile sarà trovare aiuto.

Mentre non sarai sempre in grando di trovare qualcuno che possa accollarsi l'onere, inviare un segnale incrementerà le possibilità che altre persone possano dare una mano. Prima comincerai e prima avrai persone disponibili a contribuire.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/gr2m?s=180" class="pquote-avatar" alt="avatar">

  É nel tuo interesse reclutare contributori a cui piacciono, e hanno l'attitudine per, quelle attività che tu non sei in grado di svolgere. Ti piace programmare, ma non rispondere ad issues? Identifica individui della tua community che abbiano quella predisposizione e concedile a loro.

  _\[It's in your\] best interest to recruit contributors who enjoy and who are capable of doing the things that you are not. Do you enjoy coding, but not answering issues? Then identify those individuals in your community who do and let them have it._
  <p markdown="1" class="pquote-credit">
— @gr2m, ["Welcoming Communities"](http://hood.ie/blog/welcoming-communities.html)
  </p>
</aside>

## Risolvere conflitti

Nelle prime fasi del tuo progetto, effettuare grandi decisioni è facile. Quando vuoi fare qualcosa, molto semplicemente la fai.

Man mano il tuo progetto aumenta di popolarità, più persone cominceranno ad interessarsi alle decisioni che prendi. Anche nel caso in cui tu non abbia ancora una grande community di contributors, se il tuo progetto ha parecchi utenti, riscontrerai che diverse persone vorranno esprimere la loro opinione rispetto alle tue decisioni o ti metteranno al corrente delle proprie issue.   

Generalmente, se hai coltivato una community amichevole, rispettevole e documentato il tuo procedimento in maniera aperta, la tua community dovrebbe essere in grado di trovare una risoluzione. A volte però, ti ritroverai a dover affrontare una issue più difficile.

### Sii gentile, e altri seguiranno il tuo esempio

Quando la tua community è alle prese con una issue difficile, potrebbe esserci uno scontro di diversi caratteri. Le persone si potrebbero arrabbiare, frustrarsi, prendersela con l'un l'altro o con te.

La tua responsabilità in qualità di maintainer è di evitare che le situazioni peggiorino. Anche se avessi un'opinione particolarmente forte rispetto alla discussione, prova ad adottare una posizione di moderatore o facilitatore, piuttosto che addentrarti nella mischia e imporre le tue idee. Se qualcuno è poco gentile o sta monopolizzando la conversazione, [agisci immediatamente](../building-community/#dont-tolerate-bad-actors) per far sì che la discussione rimanga civile e producente.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/kennethreitz?s=180" class="pquote-avatar" alt="avatar">

  In vece di maintainer, è estremamente importante mantenere il rispetto per i tuoi contributors. Spesso interpreteranno ciò che hai da dire molto personalmente.

  _As a project maintainer, it's extremely important to be respectful to your contributors. They often take what you say very personally._
  <p markdown="1" class="pquote-credit">
— @kennethreitz, ["Be Cordial or Be on Your Way"](https://web.archive.org/web/20200509154531/https://kenreitz.org/essays/be-cordial-or-be-on-your-way)
  </p>
</aside>

Altre persone ti terrano come punto di riferimento e guida. Sii di buon esempio. Puoi comunque esprimere disappunto, infelicità, o dubbi, ma fallo con calma.

Mantenere la tua pazienza non è semplice, ma dimostrando leadership migliorerai la salute della tua community. Internet ti ringrazia!

### Tratta il tuo README come la costituzione

Il tuo README è [più che una semplice lista di istruzioni](../starting-a-project/#writing-a-readme). É anche un luogo per parlare dei tuoi obiettivi, visione di prodotto, e roadmap. Se le persone sono eccessivamente focalizzate sul disquisire rispetto al merito di una feature in particolare, potrebbe essere utile rivisitare il tuo README e parlare della tua visione di progetto su un livello più alto. Concentrandoti sul README spersonalizzerai la conversazione, in modo da poter avere una discussione costruttiva.

### Concentrati sul viaggio, non la destinazione

Certi progetti utilizzano un processo di voto per effettuare una decisione importante. Pur sembrando una scelta saggia a primo impatto, il voto mette a risalto il raggiungimento di una "risposta", piuttosto che l'ascolto e la presa d'atto delle preoccupazioni reciproche.

Il voto può diventare politico, spingendo i diversi membri della community allo scambio di favori o ad un voto particolare. Inoltre, non tutti votano: che sia la [maggioranza silenziosa](https://ben.balter.com/2016/03/08/optimizing-for-power-users-and-edge-cases/#the-silent-majority-of-users) nella tua community, oppure utenti attuali che non erano a conoscenza della votazione.

A volte, votare non è necessariamente uno spareggio. Per quanto ti è possibile, enfatizza ["consensus seeking"](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making) piuttosto che il consenso stesso (consensus) soltanto.

Nell'ottica del raggiungimento di un consenso, i membri della community discuteranno le preoccupazioni più grandi finchè non saranno adeguatamente ascoltate. Una volta che rimangono soltanto preoccupazioni minori, la community potrà proseguire. "Consensus seeking" prende atto del fatto che la community potrebbe non essere in grado di raggiungere la risposta perfetta. Dà invece priorità all'ascolto e alla discussione.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lee-dohm?s=180" class="pquote-avatar" alt="avatar">

  Una delle ragioni per la quale un sistema di voto non esiste per le issue Atom, giace nel fatto che il team Atom non ha intenzione di seguire un sistema di voto in tutti i casi. A volte dobbiamo scegliere ciò che riteniamo giusto, nonostante sia un'opzione poco popolare. (...) Ciò che posso offrire e impegnarmi a fare... è ascoltare la mia community.  

  _Part of the reason why a voting system doesn't exist for Atom Issues is because the Atom team isn't going to follow a voting system in all cases. Sometimes we have to choose what we feel is right even if it is unpopular. (...) What I can offer and pledge to do...is that it is my job to listen to the community._
  <p markdown="1" class="pquote-credit">
— @lee-dohm on [Atom's decisionmaking process](https://discuss.atom.io/t/prioritize-issues-feature-requests-based-on-voting-system/27642/2)
  </p>
</aside>

Anche qualora non adottassi un processo consensus seeking, in qualità di project maintainer, è importante che le persone sappiano che le stai ascoltando. Facendo in modo che le persone si sentano ascoltate e impegnandoti alla risoluzione delle loro preoccupazioni, attenuerai in maniera notevole le situazioni più sensibili. Infine, segui la tua parola con azioni tue corrispondenti.

Nel tentare di raggiungere una risoluzione, non affrettarti nel prendere una decisione. Assicurati che tutti si sentano ascoltati e che tutte le informazioni siano state rese pubbliche prima di proseguire verso una risoluzione.

### Mantieni la conversazione focalizzata su azioni

La discussione è importante, ma c'è una differenza tra conversazioni producenti e poco proficue o svantaggiose.

Incoraggia la discussione finchè si sta muovendo attivamente verso una risoluzione. Se è chiaro che la conversazione languisca o cominci ad andare per la tangente, commenti diventano personali, o le persone disquisiscano su dettagli minori, è il momento di chiuderla.

Permettere che la conversazione continui non è solo gravoso per la issue in considerazione, ma dannoso alla salute della tua community. Diffonde la percezione che questo tipo di conversazioni sono permesse o persino incoraggiate, e scoraggiare le persone dal dar voce o risolverer issue in futuro.

Per ogni punto espresso da te o da altri, domandati, _"Com'è che questo punto ci avvicina ad una risoluzione?"_

Se la conversazione sta sfuggendo di mano, chiedi al gruppo, _"Quali sono i prossimi passi che dovremmo effettuare?"_ per ricentrare la conversazione.

Se è chiaro che la conversazione non sta andando da nessuna parte, non ci sono azioni chiare da prendere, o l'azione appropriata è già stata presa, chiudi la issue e spiega come mai è stata chiusa.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/kfogel?s=180" class="pquote-avatar" alt="avatar">

  Mantenere un thread in una direzione produttiva senza forzare le cose è un'arte. Ammonire le persone e chiedergli di smettere di sprecare tempo non funzionerà, come non lo sarà chiedergli di non postare finchè non abbiano qualcosa da dire di costruttivo. (...) Piuttosto, devi suggerire le condizioni necessarie per effettuare progressi ulteriori: offri alle persone una strada, una strada da seguire che le conduca ai risultati che vuoi, senza che appaia che tu stia dettando la giusta condotta.

  _Guiding a thread toward usefulness without being pushy is an art. It won't work to simply admonish people to stop wasting their time, or to ask them not to post unless they have something constructive to say. (...) Instead, you have to suggest conditions for further progress: give people a route, a path to follow that leads to the results you want, yet without sounding like you're dictating conduct._
  <p markdown="1" class="pquote-credit">
— @kfogel, [_Producing OSS_](https://producingoss.com/en/producingoss.html#common-pitfalls)
  </p>
</aside>

### Scegli le tue battaglie saggiamente

Il contesto è importante. Considera chi è compreso nella discussione e se rappresentano il resto della community.

Quanti membri della community sono arrabbiati o veramente coinvolti in questa issue? Si tratta di un caso singolo o è una issue condivisa da molti altri? Non dimenticarti di prendere in considerazione i membri della community silenziosi, non solo le "voci attive".

Se la issue non rappresenta i bisogni della tua community, potrebbe essere solamente necessario offrire un segno di riconoscimento delle preoccupazioni di alcuni. Se si tratta di una issue ricorrente senza una risoluzione chiara, indirizzali verso discussioni precedenti in un thread chiuso.

### Identifica un "community tiebreaker"

Tramite un buon atteggiamento e una chiara comunicazione, la maggior parte delle situazioni difficili saranno risolvibili. Ciononostante, anche in conversazioni produttive, ci possono essere differenze di opinione rispetto a come procedere. In questi casi, designa un individuo o gruppo di persone che agiscano come "spareggiatori".

Uno sparegiattore potrebbe essere un maintainer principale del progetto, o potrebbe essere un piccolo gruppo di persone che effettuano una decisione basata su voto. Idealmente, designerai e contrassegnerai uno spareggiatore e il processo associato in un file GOVERNANCE prima di utilizzarlo.

Il tuo spareggiatore dovrebbe essere l'ultima risorsa. Issue controverse sono una opportunità per la tua crescita e occasioni di apprendimento per i membri della tua community. Accogli queste opportunità e adopera un processo di collaborazione per orientarti verso una risoluzione ove possibile.

## La community è il ❤️ dell'open source

Community sane e in crescita alimentano le migliaia di ore investite nell'open source ogni settimana. Molti contributori attribuiscono ad altri le ragioni per le quali lavorano - o non lavorano - in progetti open source. Imparando ad accedere a quel potere in modo costruttivo, offrirai a qualcuno un'esperienza open source indimenticabile.
