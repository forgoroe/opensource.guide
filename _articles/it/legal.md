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

Condividere i frutti della tua attività creativa può essere un'esperienza stimolante ed appagante. Può anche comportare una manciata di cose legali che nemmeno credevi di doverti preoccupare. Fortunatamente, non ti tocca cominciare tutto da zero. Sappiamo quali siano i tuoi bisogni legali e ti possiamo aiutare. (Prima di cominciare, assicurati di leggere il nostro [disclaimer](/notices/).)

## Com'è che alle persone interessi così tanto il lato legale dell'open source?

Bella domanda! Quando ti cimenti in lavoro creativo (come scrittura, grafica, o codice), quel lavoro è sotto copyright esclusivo di default. Cioè, la legge presume che come autore del tuo lavoro, spetti a te dettare cosa gli altri possano farne.

Generalmente, questo significa che nessuno può utilizzare, copiare, distribuire, o modificare il tuo lavoro senza incorrere il rischio di una rimozione, shake-down, o controversia.

Tuttavia, l'Open source è una circostanze inusuale poiché l'autore si aspetta che gli altri utilizzino, modifichino, e condividano il lavoro. Ma poiché il default legale è di copyright esclusivo, hai bisogno di una licenza esplicita che affermi e conceda questi permessi.

Se non applichi una licenza open source, tutti coloro che contribuiscono al tuo progetto diventano altrettanto detentori del copyright esclusivo del lavoro. Ciò significa che nessuno può utilizzare, copiare, distribuire, o modificare i loro contributi -- e con "nessuno" si intende, te incluso.

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

La tua **compagnia** potrebbe avere requisiti di licenza specifici per i propri progetti open source. Per esempio, potrebbe richiedere una licenza permissive cosicché la compagnia abbia la possibilità di utilizzare il tuo progetto nel proprio prodotto closed source. Oppure la tua compagnia potrebbe richiedere una licenza strong copyleft e un accordo contributor aggiuntivo (vedi sotto), in modo che la tua compagnia, e nessun altro, possa utilizzare il tuo progetto in un software closed source. Oppure la tua compagnia potrebbe avere certe necessità riguardo agli standard, responsabilità sociali, o trasparenza, qualsiasi delle quali potrebbe richiedere una particolare strategia di licenza. Parla con il [dipartimento legale della tua compagnia](#what-does-my-companys-legal-team-need-to-know).

Quando crei un nuovo progetto su GitHub, ti viene data l'opzione di scegliere una licenza. Incluse quelle licenze menzionate sopra che renderanno il tuo progetto GitHub open source. Se volessi vedere altre opzioni, dai un'occhiata a [choosealicense.com](https://choosealicense.com) per trovare la licenza adatta al tuo progetto, anche se [non si trattasse di software](https://choosealicense.com/non-software/).

## E se volessi cambiare la licenza del mio progetto?

La maggior parte dei progetti non hanno mai bisogno di cambiare licenze. Occasionalmente però, le circostanze possono cambiare.

Per esempio, man mano che il tuo progetto cresce, le dependency o gli utenti incrementano di numero, o le strategie della tua compagnia cambiano, potrebbe sorgere il bisogno di una licenza diversa. Inoltre, se hai trascurato la licenza del tuo progetto dall'inizio, aggiungere una licenza equivale a cambiarla. Ci sono tre cose fondamentali da considerare quando aggiungi o cambi la licenza del tuo progetto:

**E' complesso.** Determinare la compatibilità delle licenze e chi detiene il copyright può divenire molto complesso e disorientante velocemente. Il passaggio ad una licenza nuova compatibile per nuovi rilasci e contributi è differente dal cambiare la licenza di tutti i contributi esistenti. Coinvolgi il tuo team legale al primo indizio di qualsiasi desiderio di cambiare la licenza. Anche se disponi di o puoi ottenere un permesso per un cambio di licenza da parte dei titolari del copyright di progetto, considera l'impatto che il cambio può avere sugli utenti del progetto e altri contributor. Considera un cambio di licenza come un "evento di governance" per il tuo progetto che andrà più liscio con una consultazione e una linea chiara di comunicazione con gli stakeholder di progetto. Considerati tutti questi aspetti, la scelta di una licenza appropriata fin dall'inizio è maggiormente importante!

**La licenza del tuo progetto esistente.** Se la licenza esistente del tuo progetto è compatibile con la nuova, puoi semplicemente cominciare ad utilizzare la nuova. Questo è perché se la licenza A è compatibile con la licenza B, i termini della licenza A saranno conformi con quelli della licenza B (ma non necessariamente vice versa). Quindi se stai attualmente utilizzando una licenza permissive (come per esempio, MIT), potresti passare ad una licenza con maggiori condizioni, purché tu ritenga una copia della licenza MIT e qualsiasi altro avviso di copyright associato (per esempio, continuando ad attenerti alle condizioni minime della licenza MIT). Ma se la tua licenza non è permissive (per esempio, copyleft, o non hai una licenza) e non sei il solo titolare del copyright, non puoi semplicemente cambiare la licenza di progetto 

If your project's existing license is compatible with the license you want to change to, you could just start using the new license. That's because if license A is compatible with license B, you'll comply with the terms of A while complying with the terms of B (but not necessarily vice versa). So if you're currently using a permissive license (e.g., MIT), you could change to a license with more conditions, so long as you retain a copy of the MIT license and any associated copyright notices (i.e., continue to comply with the MIT license's minimal conditions). But if your current license is not permissive (e.g., copyleft, or you don't have a license) and you aren't the sole copyright holder, you couldn't just change your project's license to MIT. Essentially, with a permissive license the project's copyright holders have given permission in advance to change licenses.

**Your project's existing copyright holders.** If you're the sole contributor to your project then either you or your company is the project's sole copyright holder. You can add or change to whatever license you or your company wants to. Otherwise there may be other copyright holders that you need agreement from in order to change licenses. Who are they? People who have commits in your project is a good place to start. But in some cases copyright will be held by those people's employers. In some cases people will have only made minimal contributions, but there's no hard and fast rule that contributions under some number of lines of code are not subject to copyright. What to do? It depends. For a relatively small and young project, it may be feasible to get all existing contributors to agree to a license change in an issue or pull request. For large and long-lived projects, you may have to seek out many contributors and even their heirs. Mozilla took years (2001-2006) to relicense Firefox, Thunderbird, and related software.

Alternatively, you can have contributors agree in advance (via an additional contributor agreement -- see below) to certain license changes under certain conditions, beyond those allowed by your existing open source license. This shifts the complexity of changing licenses a bit. You'll need more help from your lawyers up front, and you'll still want to clearly communicate with your project's stakeholders when executing a license change.

## Does my project need an additional contributor agreement?

Probably not. For the vast majority of open source projects, an open source license implicitly serves as both the inbound (from contributors) and outbound (to other contributors and users) license. If your project is on GitHub, the GitHub Terms of Service make "inbound=outbound" the [explicit default](https://help.github.com/en/github/site-policy/github-terms-of-service#6-contributions-under-repository-license).

An additional contributor agreement -- often called a Contributor License Agreement (CLA) -- can create administrative work for project maintainers. How much work an agreement adds depends on the project and implementation. A simple agreement might require that contributors confirm, with a click, that they have the rights necessary to contribute under the project open source license. A more complicated agreement might require legal review and sign-off from contributors' employers.

Also, by adding "paperwork" that some believe is unnecessary, hard to understand, or unfair (when the agreement recipient gets more rights than contributors or the public do via the project's open source license), an additional contributor agreement may be perceived as unfriendly to the project's community.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/bcantrill?s=180" class="pquote-avatar" alt="avatar">
    We have eliminated the CLA for Node.js. Doing this lowers the barrier to entry for Node.js contributors thereby broadening the contributor base.
  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.joyent.com/blog/broadening-node-js-contributions)
  </p>
</aside>

Some situations where you may want to consider an additional contributor agreement for your project include:

* Your lawyers want all contributors to expressly accept (_sign_, online or offline) contribution terms, perhaps because they feel the open source license itself is not enough (even though it is!). If this is the only concern, a contributor agreement that affirms the project's open source license should be enough. The [jQuery Individual Contributor License Agreement](https://contribute.jquery.org/CLA/) is a good example of a lightweight additional contributor agreement.
* You or your lawyers want developers to represent that each commit they make is authorized. A [Developer Certificate of Origin](https://developercertificate.org/) requirement is how many projects achieve this. For example, the Node.js community [uses](https://github.com/nodejs/node/blob/HEAD/CONTRIBUTING.md) the DCO [instead](https://nodejs.org/en/blog/uncategorized/notes-from-the-road/#easier-contribution) of their prior CLA. A simple option to automate enforcement of the DCO on your repository is the [DCO Probot](https://github.com/probot/dco).
* Your project uses an open source license that does not include an express patent grant (such as MIT), and you need a patent grant from all contributors, some of whom may work for companies with large patent portfolios that could be used to target you or the project's other contributors and users. The [Apache Individual Contributor License Agreement](https://www.apache.org/licenses/icla.pdf) is a commonly used additional contributor agreement that has a patent grant mirroring the one found in the Apache License 2.0.
* Your project is under a copyleft license, but you also need to distribute a proprietary version of the project. You'll need every contributor to assign copyright to you or grant you (but not the public) a permissive license. The [MongoDB Contributor Agreement](https://www.mongodb.com/legal/contributor-agreement) is an example this type of agreement.
* You think your project might need to change licenses over its lifetime and want contributors to agree in advance to such changes.

If you do need to use an additional contributor agreement with your project, consider using an integration such as [CLA assistant](https://github.com/cla-assistant/cla-assistant) to minimize contributor distraction.

## What does my company's legal team need to know?

If you're releasing an open source project as a company employee, first, your legal team should know that you're open sourcing a project.

For better or worse, consider letting them know even if it's a personal project. You probably have an "employee IP agreement" with your company that gives them some control of your projects, especially if they are at all related to the company's business or you use any company resources to develop the project. Your company _should_ easily give you permission, and maybe already has through an employee-friendly IP agreement or a company policy. If not, you can negotiate (for example, explain that your project serves the company's professional learning and development objectives for you), or avoid working on your project until you find a better company.

**If you're open sourcing a project for your company,** then definitely let them know. Your legal team probably already has policies for what open source license (and maybe additional contributor agreement) to use based on the company's business requirements and expertise around ensuring your project complies with the licenses of its dependencies. If not, you and they are in luck! Your legal team should be eager to work with you to figure this stuff out. Some things to think about:

* **Third party material:** Does your project have dependencies created by others or otherwise include or use others' code? If these are open source, you'll need to comply with the materials' open source licenses. That starts with choosing a license that works with the third party open source licenses (see above). If your project modifies or distributes third party open source material, then your legal team will also want to know that you're meeting other conditions of the third party open source licenses such as retaining copyright notices. If your project uses others' code that doesn't have an open source license, you'll probably have to ask the third party maintainers to [add an open source license](https://choosealicense.com/no-license/#for-users), and if you can't get one, stop using their code in your project.

* **Trade secrets:** Consider whether there is anything in the project that the company does not want to make available to the general public. If so, you could open source the rest of your project, after extracting the material you want to keep private.

* **Patents:** Is your company applying for a patent of which open sourcing your project would constitute [public disclosure](https://en.wikipedia.org/wiki/Public_disclosure)? Sadly, you might be asked to wait (or maybe the company will reconsider the wisdom of the application). If you're expecting contributions to your project from employees of companies with large patent portfolios, your legal team may want you to use a license with an express patent grant from contributors (such as Apache 2.0 or GPLv3), or an additional contributor agreement (see above).

* **Trademarks:** Double check that your project's name [does not conflict with any existing trademarks](../starting-a-project/#avoiding-name-conflicts). If you use your own company trademarks in the project, check that it does not cause any conflicts. [FOSSmarks](http://fossmarks.org/) is a practical guide to understanding trademarks in the context of free and open source projects.

* **Privacy:** Does your project collect data on users? "Phone home" to company servers? Your legal team can help you comply with company policies and external regulations.

If you're releasing your company's first open source project, the above is more than enough to get through (but don't worry, most projects shouldn't raise any major concerns).

Longer term, your legal team can do more to help the company get more from its involvement in open source, and stay safe:

* **Employee contribution policies:** Consider developing a corporate policy that specifies how your employees contribute to open source projects. A clear policy will reduce confusion among your employees and help them contribute to open source projects in the company's best interest, whether as part of their jobs or in their free time. A good example is Rackspace's [Model IP and Open Source Contribution Policy](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/vanl?s=180" class="pquote-avatar" alt="avatar">
  Letting out the IP associated with a patch builds the employee's knowledge base and reputation. It shows that the company is invested in the development of that employee and creates a sense of empowerment and autonomy. All of these benefits also lead to higher morale and better employee retention.
  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

* **What to release:** [(Almost) everything?](http://tom.preston-werner.com/2011/11/22/open-source-everything.html) If your legal team understands and is invested in your company's open source strategy, they'll be best able to help rather than hinder your efforts.
* **Compliance:** Even if your company doesn't release any open source projects, it uses others' open source software. [Awareness and process](https://www.linuxfoundation.org/blog/2015/06/why-companies-that-use-open-source-need-a-compliance-program/) can prevent headaches, product delays, and lawsuits.

<aside markdown="1" class="pquote">
  Organizations must have a license and compliance strategy in place that fits both \["permissive" and "copyleft"\] categories. This begins with keeping a record of the licensing terms that apply to the open source software you’re using — including subcomponents and dependencies.
  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Open Source Software: Compliance Basics And Best Practices"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

* **Patents:** Your company may wish to join the [Open Invention Network](https://www.openinventionnetwork.com/), a shared defensive patent pool to protect members' use of major open source projects, or explore other [alternative patent licensing](https://www.eff.org/document/hacking-patent-system-2016).
* **Governance:** Especially if and when it makes sense to move a project to a [legal entity outside of the company](../leadership-and-governance/#do-i-need-a-legal-entity-to-support-my-project).
