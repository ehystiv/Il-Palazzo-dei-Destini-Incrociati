<script setup>
import Video from '../components/Video.vue';
import Title from '../components/Title.vue';
import Card from '../components/Card.vue';
import Image from '../components/Image.vue';
import Hand from '../components/Hand.vue';
import RouterButton from '../components/RouterButton.vue';
</script>

<template>
  <Particles id="tsparticles" :particlesInit="particlesInit" :particlesLoaded="particlesLoaded" url="/particles.json" />
  <section id="video">
    <Video />
  </section>

  <Image image="castello-logo.png" />

  <section id="welcome" class="container-md mb-2 text-white">
    <Title />
  </section>

  <RouterButton to="/iscrizioni" text="Iscriviti all'evento" />

  <Hand>
    Non ti preoccupar dei <br />
    Sogni tuoi piu’ disparati <br />
    Se li hai persi o se per<br />
    Caso ti sono stati rubati<br />
    Cercarli tu potrai nei<br />
    Luoghi inesplorati<br />
    Del palazzo dei destini incrociati
  </Hand>

  <section id="sinfonia" class="container-md mb-4">
    <Card
      title="La Sinfonia dei Sette"
      incipit="Così nacque Fulcron, l’Anello, e con esso le razze dei mortali che lo abitano. Ere dopo la sua creazione,
              tanti sono i regni che i mortali hanno creato."
    >
      <p>Sette furono gli Dei. Sette cantarono e così cantando crearono il Tutto.</p>
      <p>
        La prima Hava cantando si cavò dalle viscere il cielo e lo pose sopra alla terra, poi per sua volontà, terra e
        cielo si inclinarono così da potersi incontrare.
      </p>
      <p>
        Opera del secondo, Samudra, furono i cicli dei mari, della terra e delle moltitudine delle acque. Lei costruì la
        grande scala da cui scende la pioggia.
      </p>
      <p>
        Il terzo Yud’ah cantando, si assicurò che tutti avrebbero lavorato nel grande firmamento, affondò le mani e i
        piedi nella terra e formò i metalli del sottosuolo.
      </p>
      <p>
        Samajhadara, il quarto, mise la terra dove non vi era niente, poi soffiò il vento e poiché era sapiente, lo
        chiamò spirito, perché in lui non vi era morte.
      </p>
      <p>
        Il quinto Andhera creò la notte e la morte, creò il mondo degli inferi e li destinò a chi aveva veleno
        nell'anima.
      </p>
      <p>
        Opera di Mausama, il sesto, fu la crescita delle piante e degli animali, mutò il tempo atmosferico e mosse la
        ruota nel tempo.
      </p>
      <p>
        Dall'ultimo, chiamato Surya, uscì la prima luce, e la mantenne accesa in una sfera ardente che pose nel cielo.
        <br />
        Poi con la terra impastò il fango e ne uscì una forma umanoide, poi prese dalla sfera ardente un po della luce
        che le aveva posto dentro e la posò su queste forme inanimate, così facendo nacque l'anima primordiale che si
        irradiò attraverso il corpo sprigionando l'aurea, e così gli donò la vita.
      </p>
    </Card>
  </section>

  <section id="ambientazione" class="container-md mb-5">
    <Card title="La Nostra Ambientazione"
      ><p>
        La nostra ambientazione di divide in cinque macro regioni, ognuna con caratteristiche e peculiarità proprie.
        <br />
        Non preoccuparti se non conosci a menadito l’ambientazione di Fulcron: ad ogni PGOS verranno date le
        informazioni necessarie per giocare senza problemi e, se vorrai approfondire, potrai sempre consultare la nostra
        Wikia, disponibile sul nostro sito.
      </p>
      <p>
        Il Nord, ispirato all’Europa del basso medioevo, è composto da una grande varietà di Regni. Tra i più
        significativi ricordiamo il Regno di Ilshaka, retto dal grande sovrano guerriero Nymbra Shoot, un re ormai molto
        anziano che fu decisivo nel mantenere il Nord unito in molte delle guerre del passato, e Lungacosta, regno
        affacciato sul mare governato da una regina ambiziosa, Elaine Moonsharp.
      </p>
      <p>
        L’Est, ispirato alle grandi civiltà asiatiche e nordafricane, l’Est è suddiviso in tre grandi regioni. Verso
        nord troviamo le Città Libere del Deserto, che si governano in autonomia, Tra di esse spicca Partaros, da cui si
        è originato il grande e potente Ordine dei Guaritori. Nelle Terre Verdi di Jotai sorge invece l’Impero dei
        Dodici Fiori, attualmente governato dall’autoproclamatosi imperatore Doraan. Infine, il sultanato degli Arak,
        composto da nomadi del deserto governati da un ricco e potente sultano.
      </p>
      <p>
        Il Sud, ispirato alla cultura greca e romana del mondo classico. Una grande muraglia si estendeva lungo tutto il
        confine meridionale del regno e lo separava dai Diaforos, creature orribili e bellicose. Qualche anno fa il muro
        è crollato, stravolgendo ogni equilibrio geopolitico della zona. Attualmente il Sud è frammentato e diviso:
        l’Antico Regno cerca di resistere, mentre una nuova entità territoriale, Nea Imera, è sorta con la speranza di
        unire uomini e Diaforos. Intere regioni sono perdute nell’anarchia e nel disordine mentre nelle Tre Gemme del
        Sud, ricche città di traffici e commerci, i mercanti hanno approfittato della situazione per prendere il potere.
      </p>
      <p>
        L’Ovest, ispirato alle americhe precolombiane. Grandi foreste vergini si estendono per tutto il territorio e le
        grandi potenze di Fulcron competono per colonizzare la zona. Grandi tribù di guerrieri nomadi vivono in queste
        terre.
      </p>
      <p>
        Infine, il Mare Interno, il grande oceano che si trova al centro di Fulcron e che gli conferisce la
        caratteristica forma ad Anello. Molti sono i pirati che solcano questi mari, dato che nessun regnante è mai
        stato abbastanza potente da estendere il suo controllo su di essi. Nove sono i più grandi pirati che si
        autoproclamano Nobili, guidati, se così si può dire, dal Re Bambino, mentre nel Mare di Ossa, nascosta e sempre
        in agguato Mimì Lorane, la piratessa in esilio attende il momento esatto in cui poter vendicarsi e diventare
        Regina dei Mari.
      </p></Card
    >
  </section>

  <Hand>
    In mezzo a un fitto bosco, un palazzo dava rifugio a quanti la notte aveva sorpreso in viaggio: cavalieri e dame,
    cortei reali e semplici viandanti. Passai per un ponte levatoio sconnesso, smontai di sella in una corte buia,
    stallieri silenziosi presero in consegna il mio cavallo. Ero senza fiato; le gambe mi reggevano appena: da quando
    ero entrato nel bosco tali erano state le prove che mi erano occorse, gli incontri, le apparizioni, i duelli, che
    non riuscivo a ridare un ordine né ai movimenti né ai pensieri.
  </Hand>

  <section id="palazzo" class="container-md">
    <Card
      title="Il Palazzo dei Destini Incrociati"
      incipit="Scorre, il filo del fato. 
Veloce si dipana dalla matassa. 
Corre attraverso i segreti del Tempo, mentre il Caso ridendo lo accompagna. 
Insieme, formano quella cosa che noi mortali chiamiamo Destino. 
Se tu potessi vederlo, tu che posi gli occhi su queste righe, assisteresti a uno spettacolo unico: decine di fili cangianti che si uniscono in un unico punto. La Magione de Van Gaussié. 
Qualcuno ancora nemmeno immagina che questa sia la destinazione cui è destinato, mentre altri  già godono della ospitalità del padrone di casa, Tremelech de Van Gaussié.
Ah, il magnifico ospite. 
 Molti hanno sentito parlare di lui, pochi lo hanno visto, nessuno può dire di conoscerlo. Sempre così elegante, così generoso nell'accogliere i viandanti. Un esteta. Un genio. Un folle?
Non lo sai. Come non sai chi sia a governare su queste terre di frontiera. Come non sai chi altro verrà condotto dal Destino questa sera qui, in questa villa, a questo banchetto.
Forse, è ora che prepari la tua storia, caro lettore. 
D'altronde, cosa siamo noi se non quello che diciamo di essere? Diventiamo ciò che gli altri vedono quando ci guardano, dopotutto. 
Forse, questa sera sarà più necessaria che mai una maschera. 
Indossala, caro lettore, e benvenuto.
"
    >
      <p>
        Muthalath, Komiteia, e ancora Owari. Molti sono i nomi dati nel tempo a questa terra. Così vicina a tutti da
        essere una facile conquista, ma così poco interessante da sfuggire alle brame di chiunque. Snodandosi nei
        stretti sentieri all’interno delle montagne, questa terra mette in comunicazione le ricche Gemme del Sud,
        l’orgoglioso Impero dei Dodici Fiori e l’esotico Sultanato. Eppure il passaggio è impervio, labirintico e la
        leggenda vuole che nessuno vi faccia ritorno, per questo è divenuto noto a molti come il Passo dei Perduti. Una
        villa ricca e sfarzosa si dice sia sorta all’interno di quel labirinto, lì all’incrocio della vie dove ogni
        viandante è guidato dal fato: il Palazzo dei Destini Incrociati.
      </p>

      <p>
        L’autunno è sceso sull’Impero dei Dodici Fiori, i petali lasciano i loro steli in una guerra civile che sta
        mettendo i nobili gli uni contro gli altri. Da una parte i sostenitori della casata imperiale, prossima
        all’estinzione dopo la morte dell’imperatore, e dall’altra i seguaci del nuovo imperatore, lo straniero Doraan
        di Partaros, detto Lo Scorpione.
      </p>

      <p>
        Il vento caldo del Grande Deserto porta dalle terre dell’est solo qualche flebile sussurro. Ben poco si conosce
        del misterioso Sultanato, retto dagli dei-sovrani della casata Arak. Eppure in molti hanno udito in quelle
        deboli voci terrore e insicurezza.
      </p>

      <p>
        Dal Sud giunge invece un continuo flusso di merci pregiate. Tre grandi, ricche e sfarzose città sorgono infatti
        poco lontano da Komiteia: le Tre Gemme del Sud. Un tempo poste sotto il dominio dell’Antico Regno, sono ora
        governate da mercanti spregiudicati e ambiziosi. Terre in cui il lusso e il piacere sono diventate nuove
        divinità.
      </p>
    </Card>
  </section>

  <Image image="6.png" />

  <section id="grv" class="container-md mb-4">
    <Card
      title="Il Gioco di Ruolo dal Vivo"
      incipit="Fulcron è il mondo fantastico in cui sono ambientate le nostre fantastiche storie, ma prima di addentrarti nei suoi territori inesplorati forse è meglio
parlare di cosa sia un Gioco di Ruolo dal Vivo, anche detto Larp. Per darvi un idea voglio fare un piccolo paragone che forse vi farà sorridere: tutti da bambini avete impugnato una spada o un bastone e immaginato di essere i soli eroi in grado di sconfiggere il malvagio di turno.
"
    >
      <p>
        Immagina di essere il protagonista di un film senza copione né pubblico, in cui l’attore è anche regista. Il set
        è l’intera location di gioco che hai a disposizione, ma non ci sarà nessuno a giudicarti o ad applaudirti.
        Improvvisando liberamente in modo spontaneo e naturale, sarai TU il protagonista della tua storia, insieme agli
        altri giocatori co-attori che interpreteranno con te il dramma ed il riso, il conflitto o l’unione.
      </p>

      <p>
        Immagina di essere l’autore di un romanzo ancora da scrivere, e di avere carta bianca sul finale, i legami, gli
        intrecci fra i personaggi. Di poter raccontare, inventare, creare liberamente. Dove sei TU il co-autore della
        storia ed ogni tua azione, sentimento, decisione influenza il corso della narrazione, insieme agli altri
        personaggi.
      </p>

      <p>
        Immagina di vivere una vita parallela in un mondo di finzione ricreato ad hoc tramite un’atmosfera immersiva
        grazie all’utilizzo di scenografie e costumi appositi. Un’illusione dentro la realtà, un’opportunità per
        cambiare punto di vista in un universo non così distante. Immagina di vivere in prima persona una storia unica,
        nata e creata solo nel momento in cui è vissuta dai partecipanti stessi. Un’esperienza di condivisione,
        conflitto, azione e riflessione comune.
      </p>

      <p>
        Un sipario alternativo aperto solo nell’istante in cui viene giocato, ma che continua a sopravvivere nei
        ricordi, nei legami e nelle emozioni provate dai giocatori che lo hanno vissuto.
      </p>

      <p>Questo e molto di più è il LARP.</p>
    </Card>
  </section>

  <section id="new-game" class="container-md">
    <Card
      title="Un Nuovo Modo di Giocare"
      incipit="Nel mondo del Gioco di Ruolo dal Vivo esistono essenzialmente due grandi tipologie di evento: le Campagne Continuative e le OneShot…"
    >
      <p>
        In una Campagna si interpretano gli stessi personaggi per un lungo periodo di tempo. In questo modo, si vengono
        a creare profondi legami tra di essi, si formano gruppi e si lotta per obiettivi comuni. Può essere paragonata a
        una Serie Tv, in cui i protagonisti compaiono puntata dopo puntata. In una OneShot, invece, l’evento inizia e
        finisce nel giro di qualche giorno. I personaggi interpretati vengono abbandonati, e spesso le situazioni che si
        vengono a creare sono più cariche di pathos e drammaticità. Sono paragonabili a Film: i protagonisti sono sempre
        diversi, così come le storie che vengono raccontate. La nostra idea è quella di unire queste due tipologie in
        qualcosa di nuovo, in modo da godere dei vantaggi di entrambe.
      </p>

      <p>
        C’è una storia generale, un disegno di insieme, ma ogni evento pulsa di vita propria e sa donare a qualsiasi dei
        giocatori che vi hanno partecipato grandi emozioni. Per fare questo, abbiamo pensato di dividere i personaggi in
        due categorie: i Personaggi Campagna (PG) e i Personaggi One Shot (PGOS).
      </p>

      <p>
        I PG vengono creati da voi giocatori. Potrete decidere se interpretare un pavido mercante, un tenace guerriero,
        una nobile dama, la scelta è vostra. Potrete decidere di interpretare il PG da voi creato ad ogni evento della
        Sinfonia dei Sette e per voi l’esperienza sarà quindi simile a quella di una Campagna: il vostro personaggio
        crescerà nel tempo, diventando più esperto e più forte; stringerà legami profondi con altri personaggi e, nel
        tempo, potrete dare forma alla sua storia. Per creare un PG è fondamentale scrivere un background che non deve
        essere né troppo breve ma neanche troppo articolato, ma deve descrivere al meglio la storia del vostro
        personaggio. Una volta creato è necessario inviarlo al gruppo ambientazione che lo valuterà e, se presenti, ti
        chiederà di correggere eventuali errori o incongruenze con la trama già presente.
      </p>

      <p>
        I PGOS vengono forniti in numero limitato dallo Staff, e saranno diversi per ogni evento. Sono del tutto simili
        ai personaggi che si possono trovare nelle OneShot: ognuno di essi sarà ben caratterizzato, avrà segreti,
        relazioni e obiettivi. Una volta che avrete scelto quale tra i PGOS disponibili sia più adatto per voi, tutto
        ciò che vi serve per giocare sarà indicato nella Scheda del Personaggio che vi verrà fornita dallo Staff. Sono i
        personaggi ideali per chi non può essere presente con continuità a tutti gli eventi della Sinfonia dei Sette,
        per i nuovi giocatori o per tutti coloro che amano calarsi ogni volta in una parte diversa.
      </p>

      <p>
        Negli eventi di campagna della “sinfonia dei sette” di Fulcron GRV, è possibile scegliere se partecipare come
        Personaggio Giocante (PG) o come Personaggio Giocante One Shot (PGOS). Quest’ultimo, una volta completata
        l’iscrizione potrai scegliere uno fra i tanti protagonisti di questo evento selezionando uno dei Teaser. Il
        Teaser identifica le caratteristiche chiave ed i concetti fondamentali che rendono unico quel personaggio. In
        vicinanza dell’evento ti verrà consegnata tramite mail anche la Scheda Personaggio completa di numerosi spunti
        di gioco, come segreti, relazioni, intrighi e molto altro. Si tratta di una “carta d’identità” di partenza che
        ha lo scopo di darti spunti interessanti per giocare e caratterizzare al meglio il tuo personaggio, non un
        copione da seguire. Ricordati che sarai tu a raccontare la storia del tuo personaggio...insieme agli altri
        partecipanti!
      </p>
    </Card>
  </section>

  <Image image="8.png" />

  <section id="golden-rule" class="container-md mb-4">
    <Card title="Le Regole d'Oro del LARP" align="start">
      <ul>
        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          Rimani sempre nel personaggio: con le parole, con le azioni e coi pensieri. Non uscire mai dal gioco, non
          parlare d’altro: il gioco è bello ed emozionante se tutti lo rendono vero e vivo a beneficio degli altri
          partecipanti.
        </li>
        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          A ogni azione, una reazione: se un altro personaggio ti rivela un segreto, ti insulta, ti nomina suo vice, ti
          pugnala a tradimento... reagisci. Non importa che cosa fai o dici, ma fai qualcosa, possibilmente qualcosa di
          appropriato, di divertente, di drammatico. In un larp nessuna azione deve cadere nel vuoto.
        </li>
        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          Accetta le azioni altrui: in un larp ciascuno è regista di se stesso. Non mettere mai in dubbio le azioni o la
          buona fede degli altri e non aspettarti mai da loro una reazione specifica. Prendi sempre per buono tutto
          quello che succede e gioca di conseguenza. In un larp non c’è copione, non ci sono prove e non si rigirano le
          scene; non tutto sarà perfetto, ma tutto sarà convincente, se decidi di crederci.
        </li>

        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          Quando si interpretano situazioni drammatiche insieme ad altri giocatori, è bene avere un semplice set di
          regole base per gestire al meglio il tuo coinvolgimento senza imbarazzo o fastidio. Vogliamo che tu sia in
          grado di comunicare chiaramente i tuoi limiti, e decidere l’intensità di gioco che preferisci senza
          interrompere il flusso della scena. Usa sempre il buon senso e non fare nulla di pericoloso: nessuno deve
          farsi male.
        </li>

        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          Se durante il gioco succede qualcosa che trovi troppo sgradevole o invadente, puoi (e devi!) usare la frase di
          sicurezza “Vacci piano!”: ciò indicherà all’altro giocatore che deve evitare di essere troppo realistico,
          lasciarti spazio, abbassare la tensione, badare di non farti male.
        </li>

        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          Non c’è nulla di male ad usare il “Vacci piano” e ricordati sempre di obbedire se qualcuno te lo dice:
          ciascuno ha la sua sensibilità e il suo metro di giudizio e tu devi rispettarli ciecamente.
        </li>

        <li class="list-unstyled mb-2 border-bottom border-1 border-dark">
          Più spesso, può capitare che un giocatore sia troppo prudente o timido e, non volendo rischiare di infastidire
          l’altra persona, interpreti una scena in modo fin troppo astratto. In questi casi puoi usare la frase di
          sicurezza “È tutto qui?”: indica all’altro giocatore che, se vuole, può andarci un po’ più pesante, aumentare
          l’intensità della scena.
        </li>

        <p>
          Inoltre se doveste notare che un giocatore vi si avvicina troppo, senza rispettare il distanziamento previsto
          dalle norme antiCOVID potete pronunciare la safeword “Mi manca l’aria!” accompagnandolo o meno con un gesto
          delle mani con i palmi protesi in avanti. L’altro giocatore capirà che si sta avvicinando troppo e si
          allontanerà immediatamente. Se un giocatore dovesse dimenticarsi la safeword e compie comunque il gesto
          previsto, l’altro giocatore deve ugualmente rispettare la distanza ed allontanarsi.
        </p>
      </ul>
    </Card>
  </section>

  <section id="rules" class="container-md">
    <Card title="Il Regolamento e Regole Speciali"> WIP </Card>
  </section>

  <Image image="7.png" />

  <section id="pgos" class="container-md mb-4">
    <Card
      title="I PGOS del Palazzo dei Destini Incrociati"
      incipit="Cos'è, alla fine, una maschera? <br>
        Cartapesta e vernice che, sul tuo volto, creano qualcosa di magnifico o di spaventoso?
        Al ballo c'era un uomo con una maschera da lupo e una donna con la maschera da agnello.<br>
        Non ti racconto il finale.<br>
        Ma sotto alla maschera cosa troviamo?<br>
        Pelle e parole che, sul tuo volto, creano qualcosa di magnifico o di spaventoso?
        Al ballo c'era un uomo senza una maschera, con occhi da lupo, e una ragazza con occhi birbanti.<br>
        Non ti racconto il finale.<br>
        Cosa c'è sotto la cartapesta, sotto la pelle?<br>
        Siamo altro oltre alle nostre menzogne?<br>
        Sono domande cui non conosco risposta.<br>
        Cercala tu, se lo desideri. Ma attenzione: quando provi a strappare una maschera, i lacci che tengono stretta la tua improvvisamente si fanno più lenti.<br> <br>
"
    >
      <p>
        Tutti i personaggi di questo magnifico intreccio hanno un'identità nascosta ben coperta da una colorata
        maschera. Infatti le maschere possono essere di cartapesta, altre dipinte sul volto, altre ancora le indossiamo,
        anche senza vederle fisicamente. Questo è quello che interpreterai nel palazzo, una maschera, ma attentə a
        ricordare chi eri sotto la maschera, perchè indossandola per molto tempo potresti non ricordartelo più.
      </p>
      <p>
        Post Scriptum Mi dicono che quell'uomo abbia pianto a lungo, quella notte, mentre la ragazza fuggiva. Lui rimase
        nudo sotto la maschera, lei ne trovò una nuova. O forse lei altro non aveva che il suo volto. Chi può dirlo?
      </p>

      <RouterButton to="/pgos" text="Visualizza i PGOS" />
    </Card>
  </section>

  <section id="info" class="container-md">
    <Card
      title="La Location e gli Orari"
      incipit="
      Villa Achillini, Via Helston, 40037 Sasso Marconi BO, 44.396417, 11.243677 <br>
      Sabato 23 Aprile<br><br>

      10:00 - Ritrovo ed apertura segreteria <br>
      10:30 - Trucco e preparazione<br>
      11:30 - Workshop<br>
      13:00 - Pranzo OG<br>
      14:00 - Speed Larp<br>
      14:30 - Time In<br>
      20:00 - Cena IG<br>
      <br>
      Domenica 24 Aprile<br>
      <br>
      03:00 - Time Off<br>
      "
    >
      <a
        href="
        https://www.google.com/maps/place/Via+Helston,+5,+40037+Sasso+Marconi+BO/@44.396153,11.2426492,17z/data=!3m1!4b1!4m5!3m4!1s0x132ad38f06a5b073:0x48a89bf41bbc5a20!8m2!3d44.396153!4d11.244202 
        "
        class="btn bg-white border border-2"
        target="_blank"
        >Visualizza su Maps</a
      >
      <p>
        La quota evento sarà di 10€, che comprendono la caparra, più 35€, che comprenderà tutti i pasti della giornata
        di gioco.
      </p>
      <p>
        Per avere il proprio posto assicurato, subito dopo aver compilato l’iscrizione all’evento, sarà necessario
        versare sul Paypal di “FulcronGRV” la caparra di 10€ ed inserire come messaggio il proprio nome e cognome, e il
        tipo di pagamento deve essere verso familiari e amici. <br />
        (Se hai partecipato a eventi che ti danno sconti dovrai comunque versare la caparra, lo sconto sarà applicato
        all’importo completo)
      </p>
      <p>
        Possono essere fatti anche più pagamenti con un solo paypal, l’importante è che vengano sempre inseriti tutti i
        nomi e cognomi delle persone paganti. Prima del 20 Aprile l’intera quota dovrà essere saldata sulla piattaforma
        paypal.
      </p>
      <p>
        Si ricorda a tutti i partecipanti che sarà obbligatorio esibire un GREEN PASS VALIDO la mattina del 23 Aprile
        quando si entrerà alla villa nel momento della segreteria, e di munirsi ed indossare la mascherina quando saremo
        nei luoghi interni ed affollati.
      </p>

      <RouterButton to="/iscrizioni" text="Iscriviti all'evento" />
    </Card>
  </section>

  <Image image="logo.png" />
</template>

<style></style>
