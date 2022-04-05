---
lang: it
title: Leadership e Amministrazione
description: Growing open source projects can benefit from formal rules for making decisions.
class: leadership
order: 6
image: /assets/images/cards/leadership.png
related:
  - best-practices
  - metrics
---

## Consapevolezza amministrativa per la crescita del tuo progetto

Il tuo progetto sta crescendo, la community è attiva e sei determinato a far sì che continui così. A questo punto potresti domandarti come introdurre contributor assidui nel tuo workflow, che si tratti di offrire loro commit access oppure della responsabilità alla risoluzione dei conflitti nella community. Se hai domande, noi abbiamo risposte.

## Quali ruoli ufficiali vengono utilizzati nei progetti open source?

Per quel che riguarda i ruoli di contributor e il loro riconoscimento, molti progetti  seguono una struttura simile.

Cosa implichino questi ruoli realmente sta a te. Questi sono alcuni dei ruoli che potresti riconoscere:

* **Maintainer**
* **Contributor**
* **Committer**

**Per alcuni progetti, i "maintainers"** sono le uniche persone ad avere commit access. In altri progetti, sono semplicemente le persone che vengono elencate nel README come maintainer.

Un maintainer non è necessariamente qualcuno che scrive codice per il tuo progetto. Potrebbe essere qualcuno che ha investito parecchio tempo ed energia promuovendo il tuo progetto, oppure qualcuno che abbia scritto documentazione che ha reso il progetto più accessibile. A prescindere da quello che fanno di giorno in giorno, un maintainer è probabilmente qualcuno che nutre un senso di responsabilità verso la direzione del progetto ed è determinato a migliorarlo.

**Un "contributor" potrebbe essere chiunque** commenta su una issue o pull request, chiunque apporti valore al progetto (che effettui triage delle issue, scriva codice, organizzi eventi), o chiunque abbia una pull request che è stata merged (probabilmente la più stretta delle definizioni di contributor).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mikeal?s=180" class="pquote-avatar" alt="avatar">
  \[Secondo Node.js,\] ogni persona che si fa viva per commentare su una issue o invia codice, è un membro della community del progetto. Il solo vederli è dimostrazione sufficiente per attestare che hanno superato la linea che separa l'essere un semplice utente dall'essere un contributor.

  _\[For Node.js,\] every person who shows up to comment on an issue or submit code is a member of a project’s community. Just being able to see them means that they have crossed the line from being a user to being a contributor._
  <p markdown="1" class="pquote-credit">
— @mikeal, ["Healthy Open Source"](https://medium.com/the-javascript-collection/healthy-open-source-967fa8be7951)
  </p>
</aside>

**Il termine "committer"** potrebbe essere impiegato per distinguere commit access, un tipo di responsabilità specifica, da altre forme di contributo.

Mentre sta a te definire i ruoli del progetto come preferisci, [considera l'utilizzo di definizioni più ampie](../how-to-contribute/#what-it-means-to-contribute) per incoraggiare forme di contributo diverse. Puoi utilizzare ruoli di leadership per formalmente mostrare la tua riconoscenza a coloro che hanno contributo in modo eccezionale, a prescindere dalle loro particolari competenze tecniche.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/jacobian?s=180" class="pquote-avatar" alt="avatar">
  Potresti conoscermi come il "creatore" di Django... In realtà sono il tipo che hanno assunto per lavorare su un prodotto che era già stato creata da un anno. (...) La gente sospetta che il mio successo sia dovuto alle mie abilità di programmazione... Ma alla meglio sono solo un programmatore nella media.

  _You might know me as the "inventor" of Django...but really I'm the guy who got hired to work on a thing a year after it was already made. (...) People suspect that I'm successful because of my programming skill...but I'm at best an average programmer._
  <p markdown="1" class="pquote-credit">
— @jacobian, ["PyCon 2015 Keynote" (video)](https://www.youtube.com/watch?v=hIJdFxYlEKE#t=5m0s)
  </p>
</aside>

## Come formalizzo questi ruoli di leadership?

La formalizzazione dei ruoli di leadership aiuta le persone a sentirsi proprietari del progetto e informa il resto della community chi devono interpellare per un aiuto.

Per progetti più piccoli, per nominare dei leader può essere sufficiente l'aggiunta dei loro nomi nel tuo file README o CONTRIBUTORS.

Per un progetto più grande, se hai un sito, crea una team page o elenca i leader del tuo progetto lì. Per esempio, [Postgres](https://github.com/postgres/postgres/) ha una [team page completa](https://www.postgresql.org/community/contributors/) fornita di brevi profili per ciascun contributor.

Se il tuo progetto ha una community di contributor vivaci, potresti formare un team di maintainer principale, oppure anche un sottocomitato di persone che si prendano l'incarico di aree diverse delle issue (per esempio, sicurezza, triage delle issue, o condotta della community). Lascia che le persone si auto-organizzino e si offrano a ricoprire i ruoli che trovano più stimolanti, piuttosto che assegnarli tu stesso.

<aside markdown="1" class="pquote">
  \[Noi\] affianchiamo il team principale con vari "sotto-team". Ogni sotto-team è concentrato su un'area specifica, per esempio, design di linguaggio o librerie. (...) Per garantire una coordinazione globale forte e una visione d'insieme del progetto coesa, ogni sotto-team è diretto da un membro della squadra principale.

  _\[We\] supplement the core team with several "subteams". Each subteam is focused on a specific area, e.g., language design or libraries. (...) To ensure global coordination and a strong, coherent vision for the project as a whole, each subteam is led by a member of the core team._
  <p markdown="1" class="pquote-credit">
— ["Rust Governance RFC"](https://github.com/rust-lang/rfcs/blob/HEAD/text/1068-rust-governance.md)
  </p>
</aside>

I team principali potrebbero creare un canale di comunicazione dedicato (tipo IRC) o incontrarsi regolarmente per discutere il progetto (su Gitter o Google Hangout). Inoltre, puoi rendere quegli incontri pubblici affinché gli altri possano ascoltare. [Cucumber-ruby](https://github.com/cucumber/cucumber-ruby), per esempio, [offre un orario di ricevimento settimanale](https://github.com/cucumber/cucumber-ruby/blob/HEAD/CONTRIBUTING.md#talking-with-other-devs).

Una volta che hai stabilito i ruoli di leadership, non dimenticarti di documentare come gli altri possono ottenerli! Definisci un processo chiaro da seguire per diventare maintainer, o come ci si può unire ad un sottocomitato nel tuo progetto annotandolo nel tuo GOVERNANCE.md.

Strumenti come [Vossibility](https://github.com/icecrime/vossibility-stack) ti possono essere utili a rimanere al corrente di chi sta (o non sta) contribuendo al tuo progetto. La documentazione di queste informazioni è un buon modo per evitare che venga a crearsi l'idea che i maintainer siano una sorta di cricca che effettua decisioni privatamente.

Infine, se il tuo progetto è su GitHub, considera di spostare il tuo progetto dal tuo account personale a quello di un'organizzazione e di aggiungere almeno un admin di riserva. [GitHub Organizations](https://help.github.com/articles/creating-a-new-organization-account/) rende più facile gestire permessi e repository multipli, e a proteggere il futuro del tuo progetto tramite [proprietà condivisa](../building-community/#share-ownership-of-your-project).

## Quand'è più opportuno dare a qualcuno commit access?

Alcune persone ritengono sia opportuno dare commit access a tutti coloro che contribuiscono. Così incrementando il senso di appartenenza e di proprietà condivisa del tuo progetto dei vari contributor.

D'altra parte, specialmente per progetti più grandi o più complessi, potresti preferire dare commit access soltanto a coloro che hanno dimostrato il loro impegno per più tempo. Non c'è un modo più o meno corretto di gestire la cosa - fai ciò che ti fa sentire più a tuo agio!

Se il tuo progetto è su GitHub puoi utilizzare [protected branches](https://help.github.com/articles/about-protected-branches/) per gestire chi può effettuare push su branch particolari, e in quali circostanze.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/felixge?s=180" class="pquote-avatar" alt="avatar">
  Qualunque volta qualcuno ti invia una pull request, offri loro commit access al tuo progetto. Nonostante possa a prima impatto sembrare la cosa più sciocca, utilizzando questa strategia sprigionerai il vero potenziale di GitHub. (...) Una volta che le persone hanno commit access, non si preoccupano più che la loro patch non vada accettata... Questo li ispira a lavorare più proficuamente.

  _Whenever somebody sends you a pull request, give them commit access to your project. While it may sound incredibly stupid at first, using this strategy will allow you to unleash the true power of GitHub. (...) Once people have commit access, they are no longer worried that their patch might go unmerged...causing them to put much more work into it._
  <p markdown="1" class="pquote-credit">
— @felixge, ["The Pull Request Hack"](https://felixge.de/2013/03/11/the-pull-request-hack.html)
  </p>
</aside>

## Quali sono alcune delle strutture di amministrazione più comuni per i progetti open source?

Ci sono tre strutture di amministrazione comuni associate con i progetti open source.

* **BDFL:** BDFL è l'acronimo di "Benevolent Dictator for Life". In questo tipo di struttura, una persona (solitamente l'autore iniziale del progetto) ha l'ultima parola su tutte le decisioni più importanti di progetto. [Python](https://github.com/python) è un esempio classico. Progetti più piccoli sono probabilmente BDFL di default poiché ci sono soltanto uno o due maintainer. Un progetto originalmente sviluppato da una compagnia potrebbe altrettanto entrare a far parte di questa struttura organizzativa.

* **Meritocracy:** **(Nota bene: il termine "meritocracy" ha certe connotazioni negative per alcune community e una [storia sociale e politica complessa](http://geekfeminism.wikia.com/wiki/Meritocracy).)** In una meritocracy, viene conferito ai contributor attivi del progetto (coloro che hanno dimostrato "merito") un ruolo decisionale ufficiale. Le decisioni sono solitamente fatte basate su un accordo raggiunto tramite semplice votazione. Il concetto di meritocracy è stato lanciato dalla [Apache Foundation](https://www.apache.org/); [Tutti i progetti Apache](https://www.apache.org/index.html#projects-list) sono meritocracy. I contributi possono essere soltanto fatti da individui che rappresentano se stessi, non da una compagnia.

* **Liberal contribution:** In un modello liberal contribution, le persone che fanno la maggior parte del lavoro vengono riconosciute come le più autorevoli -sulla base del lavoro in corso piuttosto che dello storico dei contributi. Le decisioni più importanti del progetto vengono attuate sulla base di un processo di ricerca dell'unanimità (discutendo le lamentele) piuttosto che esclusivamente su voto. L'obiettivo di questo modello è di includere le più svariate prospettive della community possibile. Esempli ben noti di progetti che usano il modello Liberal contribution include [Node.js](https://foundation.nodejs.org/) e [Rust](https://www.rust-lang.org/).

Quale dovresti utilizzare? Sta a te! Ogni modello ha vantaggi e svantaggi. E nonostante possano sembrare piuttosto diversi inizialmente, tutti e tre i modelli hanno più cose in comune di quanto possa sembrare. Se sei interessato ad adottare uno di questi modelli, dai un'occhiata a questi template:

* [BDFL model template](http://oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel)
* [Meritocracy model template](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel)
* [Node.js's liberal contribution policy](https://medium.com/the-node-js-collection/healthy-open-source-967fa8be7951)

## E' necessario avere i documenti d'amministrazione quando avvio il mio progetto?

Non esiste un momento giusto per trascrivere il documento d'amministrazione del tuo progetto (GOVERNANCE.md), ma diviene molto più semplice da definire una volta che hai osservato le dinamiche di comportamento della tua community. Il migliore (e più difficile) aspetto dell'amministrazione deriva dal fatto che prende forma grazie alla tua community!

Tuttavia, una documentazione iniziale sarà inevitabilmente d'aiuto nella trascrizione della tua amministrazione di progetto in toto, quindi comincia con lo scrivere ciò che riesci. Per esempio, già all'inizio del tuo progetto, puoi definire aspettative di comportamento chiare, oppure descrivere come funziona la procedura di contribuzione.

Se fai parte di una compagnia in fase di avvio di un progetto open source, è utile avere una discussione prima del lancio riguardo come la tua compagnia intende mantenere ed effettuare decisioni sul progetto in futuro. Potresti anche spiegare pubblicamente aspetti più specifici riguardo a come la tua compagnia sarà (o non sarà!) coinvolta nel progetto.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/caabernathy?s=180" class="pquote-avatar" alt="avatar">

  Assegniamo piccole squadre che in realtà lavorano a Facebook alla gestione di progetti su GitHub. Per esempio, React è diretto da un ingegnere React.

  _We assign small teams to manage projects on GitHub who are actually working on these at Facebook. For example, React is run by a React engineer._

  <p markdown="1" class="pquote-credit">
— @caabernathy, ["An inside look at open source at Facebook"](https://opensource.com/life/15/10/ato-interview-christine-abernathy-facebook)
  </p>
</aside>

## Cosa accade se i dipendenti cominciano ad inviare contributi?

Progetti open source di successo vengono utilizzati da molte persone e compagnie, alcune delle quali potrebbero successivamente avere flussi di ricavo legati al progetto. Per esempio, una compagnia potrebbe utilizzare il codice del progetto come una delle componenti in un servizio pubblicitario.

Man mano che il progetto viene utilizzato da più e più persone, coloro che hanno maggiori competenze a riguardo diventano maggiormente richieste - tu stesso potresti essere una di loro! -, e a volte verranno pagate per il lavoro che svolgono nel progetto.

E' importante trattare le attività commerciali come qualsiasi altra fonte di risorse di sviluppo del progetto. Sviluppatori pagati non dovrebbero ricevere un trattamento preferenziale rispetto a quelli non pagati, chiaramente; ogni contributo dev'essere valutato in base al loro merito tecnico. Tuttavia, ci si dovrebbe sentire a proprio agio nel dedicarsi a lavoro commerciale, e comodi nell'asserire i loro casi d'uso nel discutere a favore di un particolare miglioramento del progetto o feature.

Il "commerciale" è perfettamente compatibile con "open source". Con "commerciale" si indica semplicemente la presenza di denaro - che il software viene utilizzato nel commercio, il che è diviene più plausibile man mano che il progetto viene adottato da più persone. (Quando un software open source viene utilizzato come parte di un prodotto non-open-source, il prodotto è complessivamente e comunque di proprietà riservata, seppur, seguendo l'etica open source, possa venir utilizzato a fini commerciali o non-commerciali.)

Come qualsiasi altra persona, sviluppatori motivati a fini commerciali ottengono influenza nel progetto tramite la qualità e la quantità dei loro contributi. Ovviamente, uno sviluppatore che viene pagato per il suo tempo potrebbe essere nella condizione di fare più lavoro di una persona che non viene pagata, ma nessun problema: la remunerazione è solo uno dei molteplici fattori che potrebbero influenzare quanto uno sviluppatore apporti. Mantieni la discussione del tuo progetto concentrata sui contributi, non su fattori esterni che consentono le persone di effettuare quei contributi.

## Ho bisogno di avere una persona giuridica per sostenere il mio progetto?

Non hai bisogno di una persona giuridica per sostenere il tuo progetto a meno che tu debba gestire del denaro.

Per esempio, se vuoi creare un'attività commerciale, dovrai creare una C Corp o LLC (se abiti negli Stati Uniti). Se stai solo svolgendo lavoro contrattuale relativo al tuo progetto open source, puoi accettare denaro come unico proprietario, oppure creare una LLC (se abiti negli Stati Uniti).

Se vuoi accettare donazioni per il tuo lavoro open source, puoi disporre di un pulsante per le donazioni (usando PayPal o Striple, per esempio), ma il denaro non sarà deducibile dalle tasse, a meno che tu venga qualificato come nonprofit (a 501c3, se sei negli Stati Uniti).

Molti progetti non vogliono prendersi la briga di creare una nonprofit, e trovano invece un nonprofit sponsor fiscale. Uno sponsor fiscale accetta le donazioni a tuo nome, solitamente in cambio di una percentuale della donazione. [Software Freedom Conservancy](https://sfconservancy.org/), [Apache Foundation](https://www.apache.org/), [Eclipse Foundation](https://eclipse.org/org/foundation/), [Linux Foundation](https://www.linuxfoundation.org/projects) e [Open Collective](https://opencollective.com/opensource) sono esempi di organizzazioni che servono da sponsor fiscali per progetti open source.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/piamancini?s=180" class="pquote-avatar" alt="avatar">

  Il nostro obiettivo è quello di fornire un'infrastruttura che le community possa utilizzare affinché siano autosufficienti, creando così un ambiente dove tutti - contributor, sostenitori, sponsor - ne ottengano benefici concreti.

  _Our goal is to provide an infrastructure that communities can use to be self sustainable, thus creating an environment where everyone — contributors, backers, sponsors — get concrete benefits out of it._
  <p markdown="1" class="pquote-credit">
— @piamancini, ["Moving beyond the charity framework"](https://medium.com/open-collective/moving-beyond-the-charity-framework-b1191c33141)
  </p>
</aside>

Se il tuo progetto è strettamente legato a certi linguaggi di programmazione ed ecosistemi, potrebbero esserci certe fondazione software relative con cui puoi lavorare. Per esempio, la [Python Software Foundation](https://www.python.org/psf/) aiuta [PyPI](https://pypi.org/), il manager di package Python, e la [Node.js Foundation](https://foundation.nodejs.org/) aiuta [Express.js](https://expressjs.com/), un framework node-based.
