# GIPPO BIKE — WEBSITE UX AUDIT

**Data audit:** 11 novembre 2026 · **Viewport:** desktop 1024×768 (browser integrato) + estrazione testuale (WebFetch)
**Limiti:** mobile non ispezionato; nessun checkout completato; screenshot non disponibili (pannello del browser non in primo piano). Ogni elemento è V (verificato) salvo indicazione.

Siti analizzati: Outside Sports, Eat Sleep Cycle, Cyclexperience, evo, Florence by Bike + **baseline Gippo Bike**.

---

## 0. Baseline — gippobike.com

| Area | Osservato | Problema |
|---|---|---|
| Homepage | Hero "CYCLE THROUGH TUSCANY · SINCE 1985", slider, 6 blocchi (Usato, Noleggio bici, E-bike, Percorsi, Negozio, Vespa) | Sei porte con lo stesso peso: nessuna gerarchia fra cliente turista e cliente locale. CTA "Richiedi informazioni" sul noleggio anche se il booking online esiste |
| IA | Il negozio (E-Bike, Usato, Vendita & Assistenza) · Noleggio bici · Noleggio Vespe · Chi siamo · Percorsi (link a Komoot, RWGPS, Bikemap) · Contatti · Login | "Percorsi" porta fuori dal sito; l'officina è nascosta dentro "Vendita & Assistenza"; il login non ha una funzione evidente |
| Sales — e-bike | Solo loghi dei brand, nessun modello, nessun prezzo; "Test Ride" senza modulo | Nessun percorso d'acquisto né di prenotazione del test |
| Sales — usato | 22 bici, taglia nel titolo, ordinamento per prezzo **ma prezzo non mostrato**; rating "0 su 5" su ogni scheda | Un ordinamento per prezzo senza prezzi e un rating vuoto riducono la fiducia |
| Rental landing | Tabella chiara di 13 modelli con prezzo giorno/settimana, extra (Garmin, borsa Ortlieb, seggiolino, portabici), scelta pedali, consegna in Toscana | Buon contenuto. Ma **due flussi paralleli**: form email ("Prenotazione e-mail") e Lokki ("Prenotazione rapida") |
| Rental booking (Lokki) | `gippobike.lokki.rent` → reindirizza al **marketplace Lokki** (`lokki.rent/loueur/gippobike`); visto in francese con il browser in lingua FR; nomi prodotto misti FR/IT/EN ("Choisissez votre taille"); gravel "CUBE o BMC" mentre il sito dice Specialized Diverge; mezza giornata e giornata intera allo stesso prezzo (45 €); cancellazione gratuita fino a 15 giorni prima; 4,7/5 su 167 recensioni | L'utente lascia il brand, vede altri noleggiatori, e trova incoerenze fra sito e booking |
| Workshop | Elenco servizi (diagnosi Bosch/Yamaha/Brose, aggiornamenti software, freni e sospensioni) | Nessuna prenotazione, nessun listino o tempistica |
| Trust | Since 1985, P.IVA, social | Recensioni (167 su Lokki) non mostrate sul sito |

---

## 1. Outside Sports — outsidesports.co.nz

- **Homepage/IA:** e-commerce Shopify con menu Bikes, Rentals, Bike Workshop, Locations; barra promo (voucher loyalty, spedizione gratuita oltre una soglia).
- **Shop:** collezioni bici (`/collections/all-bikes`), carrello, 60 giorni di reso, click & collect, wallet di pagamento.
- **Rental landing:** pagina unica con blocco per sede (indirizzo, orari, telefono, email, "Book now"). FAQ con fleet per sede, età minima bambini, seggiolini e trailer.
- **Booking:** 4 step dichiarati (sede → data e ora di ritiro → bici e add-on → checkout) → email di conferma. Add-on danni: $10 (2–4 h) / $15 al giorno, fino a $500.
- **Conversion:** -15% da 4 giorni in su; contributo di $2,50 ai trail per ogni noleggio.
- **Attrito osservato:** HubTiger nei CTA e BRM nelle FAQ; link telefono di Queenstown e Te Anau diversi dai numeri mostrati.
- **Da adattare per Gippo:** blocco "cosa è incluso / extra / protezione" in ogni prodotto; spiegare il flusso in 4 step prima del CTA.

## 2. Eat Sleep Cycle — eatsleepcycle.com

- **Homepage/IA:** il brand è un'esperienza (tour, hub, café). Il noleggio ha una landing SEO ("Bike Rental Girona") con CTA ripetuti ("Book Now", "Reserve Now", "Browse Bikes").
- **Rental booking (BRM):** selettore Service = Rental; Start date/time, Return date/time; categorie Road, Gravel, E-Bike, Urban/Leisure, Time Trial, Childrens, Tour de France Packages; **elenco per modello** (es. Colnago Y1Rs Ultegra Di2 con power meter) con "Select dates to view availability". Carrello e account presenti.
- **Servizi correlati:** consegna in hotel e territorio, trasferimenti aeroportuali, nutrizione click & collect, deposito bici notturno nell'hub, WhatsApp.
- **Policy:** riconsegna entro le 17:00, penale tardiva di 20 €, nessun lucchetto né assicurazione.
- **Attrito:** FAQ con risposte spostate, testi Málaga sulla pagina Girona, nessun prezzo sulla landing.
- **Da adattare:** mostrare il fleet premium per modello e versione del gruppo; pacchetti tematici (es. "Eroica / strade bianche", "Chianti gravel weekend").

## 3. Cyclexperience — cyclex.co.uk

- **Homepage:** hero "EPIC RIDES" con due CTA equivalenti (Hire, Shop) → card Bike Hire / Bike Shop → strip di brand → carosello bici con prezzo e sconto → percorsi → tour ed eventi → badge recensioni → card officina → newsletter.
- **IA:** Hire, Shop, Workshop, Tours, Events, About, Contact. Lo shop ha categorie per uso (Mountain, Road, Gravel, Hybrid, Kids, Folding) e versioni elettriche.
- **Rental:** pagine per hub (New Forest, Dorset, Premium Road & Gravel), FAQ e T&C dedicati; booking Rentle con scelta dello store e orari.
- **Shop:** basket, messaggi di errore sullo stock, Klarna, Apple/Google Pay, condizioni di finanziamento.
- **Attrito:** prezzi di noleggio non visibili sulla landing; link gift card "#".
- **Da adattare:** doppio ingresso Noleggio / Negozio in hero; "Premium Hire" come linea separata per corsa e gravel di alta gamma (Gippo ha Wilier Cento10 SL eTap).

## 4. evo — evo.com

- **IA:** e-commerce nazionale con sezioni Rentals e Services; pagina rental unica che elenca 7 sedi e i servizi disponibili per ognuna.
- **FAQ chiave:** credito noleggio fino a $450 sull'acquisto di una bici della stagione corrente entro 30 giorni, solo in negozio, escluso usato/demo.
- **Non verificato:** step di prenotazione, prezzi.
- **Da adattare:** regola "rent-to-buy" semplice, con tetto e finestra temporale espliciti.

## 5. Florence by Bike — florencebybike.it

- **IA:** Bonus & news, Il Negozio, Noleggio, Officina, Itinerari, Contatti. Itinerari raggruppati per distanza e durata.
- **Rental:** CTA "PRENOTA ADESSO LA TUA BICICLETTA" → Lokki (marketplace esterno, come Gippo).
- **Shop:** WooCommerce con carrello e account.
- **Attrito:** banner cookie in inglese sul sito italiano; nessun prezzo di noleggio in pagina.
- **Da adattare:** stesso stack di Gippo; la differenza la faranno contenuto, coerenza del catalogo Lokki ed embedding.

---

## 6. Pattern di conversione trasversali

1. **Doppio ingresso chiaro** (Hire / Shop) in hero — Cyclex.
2. **Booking date-first** con disponibilità reale e modello specifico — Eat Sleep Cycle.
3. **Trasparenza su cosa è incluso, extra e protezione** — Outside Sports, REI.
4. **Sconto multi-day esplicito** — Outside Sports.
5. **Credito rent-to-buy** — evo.
6. **Social proof integrato** nella pagina — Cyclex, E-Bike Toscana.
7. **Contatto rapido WhatsApp** sulle pagine di noleggio — Eat Sleep Cycle.
8. **Una pagina per sede/servizio** con orari, contatti e booking — Outside Sports.

## 7. Gap Gippo → opportunità (sintesi; dettaglio in `REDESIGN_OPPORTUNITIES.md`)

| Gap | Pattern di riferimento |
|---|---|
| Booking fuori brand e form duplicato | Booking incorporato o in sottodominio brandizzato, un solo CTA (ESC, Outside) |
| Catalogo Lokki incoerente con il sito | Una sola fonte di verità per il fleet (ESC) |
| Usato senza prezzo, anno, condizioni | Scheda usato certificata (Rebike) |
| E-bike senza modelli né test ride prenotabile | Prenotazione del test ride + credito noleggio (evo) |
| Officina senza prenotazione | "Book a Service" (Cyclex) |
| Recensioni non sul sito | Widget recensioni (Cyclex, E-Bike Toscana) |
