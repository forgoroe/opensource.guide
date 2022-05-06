---
lang: it
title: Metriche Open Source
description: Effettua decisioni consapevoli affinché il tuo progetto open source prosperi, monitorando e misurandone il successo.
class: metrics
order: 9
image: /assets/images/cards/metrics.png
related:
  - finding
  - best-practices
---

## Che utilità ha la misurazione?

Dati, quando utilizzati correttamente, possono aiutarti a prendere decisioni migliori in qualità di maintainer open source.

Con maggiori informazione, potrai:

* Capire come gli utenti rispondono a nuove feature
* Capire la provenienza di nuovi utenti
* Identificare, e decidere se supportare o meno un caso d'uso particolare o funzionalità
* Quantificare la popolarità del tuo progetto
* Capire come il tuo progetto viene utilizzato
* Raccogliere fondi tramite sponsor e finanziamenti

Per esempio, [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Analytics.md) ha constatato che Google Analytics può essere utile a stabilire quali siano le priorità del lavoro:

> Homebrew viene offerto gratis ed è mantenuto totalmente da volontari nel loro tempo libero. Di conseguenza, non abbiamo le risorse per eseguire analisi d'utente per decidere come meglio progettare feature future e stabilire le priorità rispetto al lavoro corrente. Aggregati statistici anonimi degli utenti ci permettono di stabilire quali fix e feature siano le migliori, e dove e quando le persone utilizzano Homebrew.

La popolarità non è tutto. Tutti approcciano l'open source per ragioni differenti. Se il tuo obiettivo in qualità di open source maintainer è di esporre il tuo lavoro, sii trasparente riguardo il tuo codice, oppure divertiti, le statistiche o misurazioni potrebbero non esserti d'interesse, e va bene così.

Se invece _sei_ interessato a capire il tuo progetto in modo più approfondito, continua a leggere per analizzare l'attività del tuo progetto.

## Visibilità

Prima che chiunque possa utilizzare o contribuire al tuo progetto, occorre che sappiano che esiste! Domandati: _le persone riescono a trovare questo progetto?_

![Traffic graph](/assets/images/metrics/repo_traffic_graphs_tooltip.png)

Se il tuo progetto è hosted su GitHub, puoi [visualizzare](https://help.github.com/articles/about-repository-graphs/#traffic) quante persone "atterrano" sul tuo progetto e da dove vengono. Dalla pagine del tuo progetto, clicca su "Insights", e poi "Traffic". Su questa pagina, puoi vedere:

* **Total page views:** Ti informa su quante volte il tuo progetto è stato visualizzato

* **Total unique visitors:** Ti informa sulla quantità di persone individuali che hanno visualizzato il tuo progetto

* **Referring sites:** Ti informa sulla loro provenienza. Questa statistica ti può aiutare a capire dove mirare i tuoi sforzi affinché raggiungano il tuo audience e per verificare se i tuoi tentativi di promozione stanno funzionando.

* **Popular content:** Ti informa su dove la maggior parte dei visitor vanno sul tuo progetto, diviso in page views e unique visitors.

[GitHub stars](https://help.github.com/articles/about-stars/) può anche essere utile a misurare la popolarità del progetto di base. Seppur GitHub stars non sia strettamente indicativo dei download e degli utilizzi, possono informarti delle quantità di persone che hanno preso atto del tuo lavoro.

Potresti anche voler [tenere sott'occhio la visibilità in punti più specifici](https://opensource.com/business/16/6/pirate-metrics): per esempio, Google PageRank, traffico dal sito del progetto stesso, oppure rinvii da parte di altri progetti open source o siti web.

## Utilizzo

Persone online hanno trovato il tuo progetto su questo grande, pazzo posto che chiamiamo internet. Idealmente, una volta che vedono il tuo progetto, si sentiranno spinti a far qualcosa. La seconda domanda che ti vorrai chiedere è: _le persone stanno usando questo progetto?_

Se usi un package manager, come npm oppure RubyGems.org per distribuire il tuo progetto, potresti essere in grado di monitorarne i download.

Ciascun package manager potrebbe utilizzare una definizione leggermente diversa di "download", e i download di per sé non sono necessariamente indicativi di installazioni o utilizzi, ma possono comunque essere utili ad avere un punto di riferimento e paragone. Prova ad utilizzare [Libraries.io](https://libraries.io/) per monitorare le statistiche d'utilizzo su molteplici package manager popolari.

Se il tuo progetto è su GitHub, accedi di nuovo alla pagina "Traffic". Puoi utilizzare il [clone graph](https://github.com/blog/1873-clone-graphs) per vedere quante volte il tuo progetto è stato clonato in un determinato giorno, dividendo i dati in clones totali e clones unici.

![Clone graph](/assets/images/metrics/clone_graph.png)

Se l'utilizzo del progetto rispetto al numero di persone che hanno scoperto il tuo progetto è basso, ci sono due questioni da considerare:

* Il tuo progetto non sta convertendo il tuo audience, oppure
* Stai attraendo un'audience sbagliata

Per esempio, se il tuo progetto si ritrova sulla prima pagina di Hacker News, potresti avere un alto picco di visibilità (traffico), ma un tasso di conversione basso. Questo perché stai raggiungendo tutti su Hacker News. Se il tuo progetto Ruby venisse invece presentato ad una conferenza Ruby, è più probabile che tu abbia un tasso di conversione da un audience mirato più alto.

Cerca di capire da dove viene il tuo audience e richiedi feedback sulla pagina del progetto per capire quali fra queste due problematiche stai effettivamente avendo.

Una volta che conosci le persone che utilizzano il tuo progetto, potresti voler provare a scoprire cosa ne facciano. Stanno sviluppando ulteriori feature dopo aver effettuato una fork? Lo stanno utilizzando per scopi scientifici o a fini commerciali?

## Fidelizzazione

Le persone stanno trovando il tuo progetto e lo stanno utilizzando. La prossima domanda che vuoi farti è: _le persone stanno contribuendo a questo progetto?_

Non è mai troppo presto per cominciare a pensare ai contributor. Senza persone che danno una mano, rischi di metterti in una situazione insalubre dove il tuo progetto è _popolare_ (molti lo utilizzano) ma non _supportato_ (non ci sono abbastanza maintainer per soddisfare le richieste).

La fidelizzazione richiede anche un regolare [afflusso di nuovi contributor](http://blog.abigailcabunoc.com/increasing-developer-engagement-at-mozilla-science-learning-advocacy#contributor-pathways_2), poiché contributor attivi precedenti prima o poi se ne andranno per la loro strada.

Esempi di metriche della community che potresti voler monitorare regolarmente includono:

* **Total contributor count e number of commits per contributor:** Ti dice quanti contributor hai, e chi è più o meno attivo. Su GitHub, puoi vedere questo tipo di informazione su "Insights" -> "Contributor". Così com'è, il grafico tiene conto soltanto dei contributor che hanno effettuato commit sul branch predefinito della repository.

![Contributor graph](/assets/images/metrics/repo_contributors_specific_graph.png)

* **First time, casual, and repeat contributors:** Ti aiuta a monitorare se stai acquisendo nuovi contributor, e se stanno ritornando. (Contributor casual sono contributor con un numero basso di commit. Che si tratti di un commit, meno di cinque commit, o un altro numero sta a te). Senza nuovi contributor, la community del tuo progetto può divenire statica.

* **Number of open issues and open pull requests:** Se questi numeri divengono troppo alti, potresti aver bisogno di aiuto con il triage e le revisioni del codice.

* **Number of _opened_ issues and _opened_ pull requests:** Issue aperte sono una buona indicazione che il tuo progetto importa abbastanza a qualcuno da aprire una issue. Se col passare del tempo questo numero incrementa, significa che le persone sono interessate al tuo progetto.

* **Types of contributions:** Per esempio, commit, correzione errori di battitura, bug, o commenti su una issue.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/arfon?s=180" class="pquote-avatar" alt="avatar">

  L'Open source si tratta di più di semplice codice. Progetti open source di successo includono codice e contributi alla documentazione oltre che a conversazioni rispetto a questi cambiamenti.

  _Open source is more than just code. Successful open source projects include code and documentation contributions together with conversations about these changes._
  <p markdown="1" class="pquote-credit">
— @arfon, ["The Shape of Open Source"](https://github.com/blog/2195-the-shape-of-open-source)
  </p>
</aside>

## Attività di maintainer

Infine, vorrai chiudere il cerchio assicurandoti che i maintainer del tuo progetto siano in grado di gestire il volume di contributi ricevuti. L'ultima domanda che vuoi porti è: _Sto (stiamo) rispondendo alla nostra community?_

Maintainer indifferenti diventano un collo di bottiglia per i progetti open source. Se qualcuno invia un contributo ma non riceve mai una risposta da un maintainer, potrebbero scoraggiarsi ed andarsene.

[Ricerca da parte di Mozilla](https://docs.google.com/presentation/d/1hsJLv1ieSqtXBzd5YZusY-mB8e1VJzaeOmh8Q4VeMio/edit#slide=id.g43d857af8_0177) dimostra che la tempestività della risposta da parte dei maintainer è un elemento critico nell'incoraggiamento di contributi successivi.

Considera il monitoraggio di quanto tempo impieghi (o impiega un altro maintainer) a rispondere ad un contributo, che si tratti di una issue o di una pull request. Rispondere non richiede azioni particolari. Può essere semplice come dire: _"Grazie per il tuo contributo! Lo revisionerò entro settimana prossima."_

Potresti anche misurare il tempo che ci vuole per passare da uno stage all'altro nel processo di contribuzione, come per esempio:

* Tempo di apertura media per una issue (prima che venga chiusa)
* Se le issue vengono chiuse con PRs
* Se issue più vecchie vengono chiuse
* Tempo di merge medio per una pull request

## Utilizza 📊 per conoscere meglio le persone

Una comprensione delle metriche ti sarà d'aiuto nel costruire un progetto open source attivo e sempre in crescita. Anche se non volessi monitorare ogni metrica su una bacheca, utilizza il framework delineato sopra per concentrare la tua attenzione su quei tipi di comportamenti che contribuiranno alla crescita del tuo progetto.
