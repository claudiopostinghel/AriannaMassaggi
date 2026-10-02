# Come leggere i dati del sito, ogni settimana

Questa guida serve a capire **da dove arrivano le persone che ti prenotano**, così puoi decidere dove vale la pena mettere tempo (e magari soldi): Instagram, Google, Facebook, lo stato di WhatsApp, i QR in studio e sui biglietti.

Il percorso che misuriamo è questo:

**da dove arriva → visita il sito → tocca "Prenota un massaggio" → ti scrive su WhatsApp → prenota**

I primi tre passi li conta il sito da solo. Gli ultimi due li vedi tu su WhatsApp, grazie al codice "rif." che trovi nei messaggi.

## 1. Metti i link giusti (una volta sola)

Ogni posto ha il suo link. Usa sempre quello, così il sito capisce da dove arriva la persona.

| Dove | Link da usare | Codice nel messaggio |
|---|---|---|
| Bio di Instagram | ariannamassaggi.it/ig | IG |
| Storie di Instagram (sticker link) | ariannamassaggi.it/storie | IGS |
| Scheda Google, campo "Sito web" | ariannamassaggi.it/g | GB |
| Scheda Google, campo "Prenota" | ariannamassaggi.it/prenota | GBP |
| Pagina Facebook, campo "Sito web" | ariannamassaggi.it/fb | FB |
| Post su Facebook | ariannamassaggi.it/fb-post | FBP |
| Stato di WhatsApp | ariannamassaggi.it/stato | WA |
| QR sul cartello in studio | ariannamassaggi.it/qr-studio | QS |
| QR sul biglietto da visita | ariannamassaggi.it/qr-biglietto | QB |
| Chi arriva in altro modo (passaparola, link copiato, ricerca del nome) | nessun link speciale | SITO |

Tutti i link completi sono nel file `link-utm.csv`.

## 2. Su WhatsApp: guarda il codice

Quando qualcuno tocca "Prenota un massaggio" sul sito, WhatsApp si apre con un messaggio già scritto, per esempio:

> Ciao Arianna, vorrei prenotare un massaggio. (rif. IG)

"rif. IG" vuol dire che quella persona è arrivata dalla bio di Instagram. Consiglio: in WhatsApp Business crea un'**etichetta per ogni codice** (IG, Google, QR...) e mettila alla chat. Quando la persona prenota davvero, aggiungi anche l'etichetta "Prenotato".

A volte il codice non c'è: la persona l'ha cancellato, oppure ti ha scritto senza passare dal sito. Va bene così, segnala come "senza codice".

## 3. Ogni lunedì, 5 minuti

1. **Apri la dashboard** "Arianna: la settimana": LINK_DASHBOARD
2. **Visite per settimana.** Ogni colore è un canale. Ti dice quante persone sono arrivate sul sito e da dove.
3. **Clic su WhatsApp per settimana.** Quante persone hanno toccato "Prenota un massaggio", divise per canale.
4. **Dalla visita al clic (funnel).** Per ogni canale ti dice che percentuale di chi visita il sito poi tocca WhatsApp. Esempio: "instagram 8%" vuol dire che su 100 persone arrivate da Instagram, 8 hanno aperto WhatsApp per scriverti.
5. **Cosa interessa di più.** Quali gruppi di massaggi le persone guardano (sportivo, relax, donna) e quali domande frequenti aprono. Utile per capire di cosa parlare nei post.
6. **Su WhatsApp conta** i messaggi della settimana per codice e quanti sono diventati prenotazioni. Segnali nella tabellina qui sotto.

| Settimana | Canale | Visite | Clic WhatsApp | Messaggi ricevuti | Prenotazioni |
|---|---|---|---|---|---|
| es. 6-12 ottobre | Instagram (IG + IGS) | 40 | 4 | 3 | 2 |
| | Google (GB + GBP) | | | | |
| | QR (QS + QB) | | | | |
| | Facebook (FB + FBP) | | | | |
| | Stato WhatsApp (WA) | | | | |
| | Diretto / passaparola (SITO) | | | | |

## 4. Come decidere

- **Non decidere dopo una settimana.** Con numeri piccoli basta una persona in più o in meno per cambiare tutto. Guarda il totale di 4-6 settimane.
- **Conta le prenotazioni, non le visite.** Un canale con tante visite e nessuna prenotazione vale meno di uno con poche visite che prenotano.
- **"Diretto" non è un errore.** Sono le persone che scrivono l'indirizzo a mano, aprono un link mandato da un'amica o arrivano da Instagram senza passare dal link della bio. Spesso è il passaparola.
- **Prova una cosa alla volta.** Se fai una settimana di storie con il link, guarda se salgono le visite "instagram / storie" e i messaggi "rif. IGS".

## Da sapere

- Il sito **non usa cookie** e non sa chi sono le persone: conta solo visite e clic, in modo anonimo. Per questo chi torna dopo qualche giorno viene contato di nuovo come visita nuova.
- Anche le tue visite al sito vengono contate. Non è un problema, ma non serve aprirlo ogni giorno per controllare.
- I link brevi (ariannamassaggi.it/ig e gli altri) funzionano solo dopo il passaggio del sito su Cloudflare. Fino ad allora usa i link completi del file `link-utm.csv`.
