Modello per i dati aperti
=========================

.. note::
 **AZIONE 3: VERIFICA LA CONFORMITA' AL MODELLO PER I DATI APERTI...**

 Si adotta il modello qualitativo per i dati aperti sul Web, noto come modello a cinque stelle, così come rappresentato in  Figura 2. In particolare, si raccomanda un percorso graduale verso la produzione nativa di Linked Open Data – LOD (livello cinque stelle), iniziando dal livello 3 di Figura 2.

 Produzione e pubblicazione di dati aperti *solo* di livello 1 e 2 non sono più ammessi: quest’ultimi devono essere accompagnati da quelli che rispecchiano le caratteristiche dei livelli 3 e/o superiori (per esempio, rilasciare dati strutturati solo in excel con licenza  aperta non è ammesso; questi devono essere sempre affiancati da dati strutturati in formato non proprietario).

.. figure:: _images/Dati.png
    :width: 85%
    :align: center
    :alt: Figura 2: Modello a cinque stelle per i dati aperti - rivisitazione della `figura nota e disponibile sul Web <http://5stardata.info/en/>`__

    Figura 2: Modello a cinque stelle per i dati aperti - rivisitazione della `figura nota e disponibile sul Web <http://5stardata.info/en/>`__


I livelli del modello per i dati aperti
---------------------------------------

Livello 1
^^^^^^^^^

.. figure:: _images/Dati1.png
    :width: 10%
    :alt: Livello 1


+ **Informazione**: Dati disponibili tramite una licenza aperta e inclusi in documenti  leggibili e interpretabili solo grazie a un significativo intervento umano (e.g., PDF);
+ **Accesso**: Prevalentemente umano, necessario anche per dare un senso ai dati inclusi nei documenti;
+ **Servizi**: Solo rilevanti interventi umani di estrazione ed elaborazione dei possibili dati consentono di sviluppare servizi con l’informazione disponibile in questo livello.


Livello 2
^^^^^^^^^

.. figure:: _images/Dati2.png
    :width: 10%
    :alt: Livello 2


+ **Informazione**: Dati disponibili in forma strutturata e con licenza aperta. Tuttavia, i formati sono proprietari (e.g., Excel) e un intervento umano è fortemente necessario per un’elaborazione dei dati;
+ **Accesso**: I programmi possono elaborare i dati ma non sono in grado di interpretarli; pertanto è necessario un intervento umano al fine di scrivere programmi ad-hoc per il loro utilizzo;
+ **Servizi**: Servizi ad-hoc che devono incorporare i dati per consentire un accesso diretto via Web agli stessi.

Livello 3
^^^^^^^^^
.. figure:: _images/Dati3.png
    :width: 10%
    :alt: Livello 3

+ **Informazione**: Dati con caratteristiche del livello precedente ma in un formato non proprietario (e.g.,  CSV, JSON, geoJSON). I dati sono leggibili da un programma ma l'intervento umano è necessario per una qualche elaborazione degli stessi;
+ **Accesso**: I programmi possono elaborare i dati ma non sono in grado di interpretarli; pertanto è necessario un intervento umano al fine di scrivere programmi ad-hoc per il loro utilizzo;
+ **Servizi**: Servizi ad-hoc che devono incorporare i dati per consentire un accesso diretto via Web agli stessi.

Livello 4
^^^^^^^^^
.. figure:: _images/Dati4.png
    :width: 10%
    :alt: Livello 4

+ **Informazione**: Dati con caratteristiche del livello precedente ma esposti usando standard W3C quali RDF e SPARQL I dati sono descritti semanticamente tramite metadati e ontologie;
+ **Accesso**: I programmi sono in grado di conoscere l'ontologia di riferimento e pertanto di elaborare i dati quasi senza ulteriori interventi umani;
+ **Servizi**: Servizi, anche per dispositivi mobili, che sfruttano accessi diretti a Web per reperire i dati di interesse.


Livello 5
^^^^^^^^^
.. figure:: _images/Dati5.png
    :width: 10%
    :alt: Livello 4

+ **Informazione**: Dati con caratteristiche del livello precedente ma collegati a quelli esposti da altre persone e organizzazioni (i.e., Linked Open Data [2]_). I dati sono descritti semanticamente tramite metadati e ontologie. Essi seguono il paradigma RDF (si veda `Architettura dell’informazione del settore pubblico <arch.html>`__), in cui alle “cose” (o entità) è assegnata un URI univoca sul Web. Conseguentemente tale URI può essere utilizzata per effettuare accessi diretti alle informazioni relative a quella entità. I dati sono detti “linked” per la possibilità di referenziarsi (i.e., “collegarsi”) tra loro. Nel referenziarsi, si usano relazioni (“link”) che hanno un preciso significato e spiegano il tipo di legame che intercorre tra le due entità coinvolte nel collegamento. I Linked (Open) Data sono quindi un metodo elegante ed efficace per risolvere problemi di identità e provenienza, semantica, integrazione e interoperabilità. **Triple RDF i cui URI non siano utilizzabili da un agente Web per recuperare le informazioni a essi associati, non possono essere considerati pienamente conformi al paradigma Linked Data**. Nei caso dei Linked Open Data l'intervento umano si può ridurre al minimo e talvolta addirittura eliminare;
+ **Accesso**: II programmi sono in grado di conoscere l'ontologia di riferimento e pertanto di elaborare i dati quasi senza ulteriori interventi umani;
+ **Servizi**: Servizi, anche per dispositivi mobili, che sfruttano sia accessi diretti a Web sia l'informazione ulteriore catturata attraverso i *link* dei dati di interesse, facilitando il mashup di dati.


.. rubric:: Bibliografia

.. [2]
   https://www.ted.com/talks/tim_berners_lee_on_the_next_web?nolanguage=en%2C ;   https://www.w3.org/DesignIssues/LinkedData.html ;  http://linkeddatabook.com/editions/1.0/ ; http://linkeddata.org/home
