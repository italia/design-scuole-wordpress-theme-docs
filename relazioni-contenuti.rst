Relazioni tra i contenuti
==========================

I siti WordPress presentano una serie di tipologie di contenuto (content type) che sono in relazione tra loro. Ogni tipologia di contenuto viene creata attraverso una “scheda” nel backend di WordPress, che presenta i vari campi dove aggiungere i contenuti per creare la pagina.

Questa impostazione permette di combinare i vari elementi per la creazione delle pagine, così che i contenuti vengano creati soltanto una volta e poi riutilizzati, se necessario, in varie parti del sito. Una volta comprese le relazioni tra le tipologie di contenuti, sarà facile creare le pagine del sito.

Alcune relazioni tra tipologie di contenuti, sono:

* Strutture organizzative - Servizi;
* Progetti - Persone;
* Strutture organizzative - Luoghi;
* Servizi - Documenti.

Questo significa, ad esempio, che ogni pagina di una struttura organizzativa può presentare una relazione con contenuti come i luoghi e i servizi.

.. attention::
  Dal punto di vista pratico, è necessario che i contenuti che si vuole collegare vengano creati in un ordine preciso: prima i content type che fungono da contenuti di dettaglio e poi il content type contenitore (es. prima i servizi, i luoghi e le persone e solo dopo la struttura organizzativa che raggruppa servizi, luoghi, persone creati in precedenza).

Per collegare tra loro diverse tipologie di contenuto, quindi:

1. crea la scheda o le schede dei contenuti di dettaglio (ad esempio, il luogo “Palazzo Baldini” che verrà associato ad una struttura organizzativa);
2. crea la scheda del contenuto contenitore (ad esempio, la scheda della struttura organizzativa “Segreteria scolastica”);
3. associa, tramite l’apposito campo, le schede contenuto di dettaglio alla scheda contenuto (ad esempio, il luogo “Palazzo Baldini” alla struttura organizzativa “Segreteria scolastica”).

Per associare nuovi contenuti di dettaglio ad altri già esistenti:

1. crea la nuova scheda di contenuto di dettaglio (ad esempio, la scheda servizio “Pagamento mensa scolastica” da associare alla scheda del contenuto contenitore “Segreteria scolastica”);
2. entra nella scheda del contenuto contenitore e, tramite l’apposito campo, associa la scheda del contenuto di dettaglio (la scheda servizio “Pagamento mensa scolastica” alla scheda “Segreteria scolastica”).


Nella maggior parte dei casi questa correlazione è bidirezionale e automatica. Quando si crea, ad esempio, una relazione tra un luogo e una struttura, questa verrà mostrata sia nel dettaglio del luogo che in quello della struttura.
