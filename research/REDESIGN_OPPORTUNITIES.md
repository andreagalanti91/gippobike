# GIPPO BIKE — REDESIGN OPPORTUNITIES

**Data:** 11 novembre 2026 · **Stato:** PROPOSED — nessuna raccomandazione è approvata
**Vincoli rispettati:** D-001 (WordPress + Salient + WPBakery + child theme) · D-002 (l'IA attuale è il punto di partenza; ogni modifica strutturale va approvata) · D-003 (Canyon/Specialized solo come reference, non da copiare)

---

## 1. Posizionamento proposto

> **Gippo Bike: il punto di partenza per pedalare in Val d'Elsa. Dal 1985 la provi, la noleggi, te la portiamo, e se ti innamori la compri.**

Il differenziale non è un singolo servizio ma la **continuità** fra noleggio, prova, acquisto e assistenza. Nessun competitor analizzato la comunica.

## 2. Raccomandazioni

| # | Osservazione | Evidenza | Problema utente / business | Raccomandazione per Gippo | Impatto | Complessità | Priorità |
|---|---|---|---|---|---|---|---|
| R1 | Gippo ha due flussi di booking (form email + Lokki) e Lokki porta al marketplace | Audit Gippo, Lokki (V) | Utente confuso, esce dal brand, vede altri noleggiatori; lo staff gestisce richieste doppie | **Un solo CTA "Prenota"** per bici. Verificare con Lokki widget/embed o sottodominio brandizzato; il form email resta solo per gruppi/richieste speciali | Alto | Bassa–Media (dipende da Lokki) | **P0** |
| R2 | Catalogo Lokki incoerente con il sito (lingua mista, modelli diversi, mezza giornata = giornata) | Lokki gravel (V) | Perdita di fiducia, contestazioni al ritiro | Audit e pulizia del catalogo Lokki: nomi IT/EN, modello reale, tariffe coerenti, foto; definire una sola fonte di verità del fleet | Alto | Bassa | **P0** |
| R3 | Homepage con 6 porte di peso uguale | Audit Gippo; Cyclex (V) | Il turista e il cliente locale non trovano subito il proprio percorso | Hero con **due ingressi**: "Noleggia" (turista) e "Negozio & Officina" (locale). Blocchi secondari: Usato, Percorsi, Vespa | Alto | Bassa (WPBakery) | **P0** |
| R4 | Prezzi di noleggio chiari sul sito ma CTA "Richiedi informazioni" in home | Audit Gippo (V) | Il CTA suggerisce che non si possa prenotare | CTA "Prenota online · da 20 €/giorno" in homepage e nelle card | Medio | Bassa | **P0** |
| R5 | Recensioni (4,7/5 su 167) solo su Lokki | Lokki (V); Cyclex, E-Bike Toscana (V) | Social proof non sfruttato nel momento della decisione | Widget recensioni Google/Lokki su home e noleggio | Medio | Bassa (plugin) | **P0** |
| R6 | evo scala il noleggio sull'acquisto | evo FAQ (V) | Il noleggio non genera vendite; il cliente indeciso non ha un incentivo | **"Prova e compra"**: credito di parte del noleggio e-bike/gravel sull'acquisto entro X giorni. Regola, tetto e marchi da definire con il cliente | Alto | Bassa (regola commerciale) / Media (tracciamento) | **P1** |
| R7 | Usato senza prezzo, anno, condizioni; rating "0 su 5" | Audit Gippo (V); Rebike (V) | Nessun valore percepito, nessuna fiducia | Scheda usato: prezzo, anno, taglia, km o ore motore (e-bike), stato, intervento eseguito, garanzia Gippo, foto multiple; rimuovere i rating vuoti | Alto | Media (WooCommerce già presente) | **P1** |
| R8 | Fleet del noleggio venduto a fine stagione | E-Bike Toscana (V) | Il fleet è un asset che perde valore | Sezione "Ex noleggio" dentro Usato, con storico di manutenzione | Medio | Bassa | **P1** |
| R9 | Pagina E-bike senza modelli né test ride | Audit Gippo (V) | Domanda esistente non catturata | Catalogo e-bike con modelli e "Prenota un test ride" (data, modello, contatto). Valutare l'e-commerce solo dopo i requisiti (WS03) | Alto | Media | **P1** |
| R10 | Officina senza prenotazione né tempistiche | Audit Gippo; Cyclex (V) | Telefonate e attese; diagnosi e-bike sotto-comunicata | Pagina "Officina" dedicata con pacchetti (tagliando, diagnosi e-bike, sospensioni), prezzi "a partire da" e richiesta appuntamento | Medio | Bassa–Media | **P1** |
| R11 | Policy chiare e semplici (REI), protezione danni (Outside) | REI FAQ, Outside (V) | Ansia su deposito, danni, cancellazione | Box "Cosa è incluso · Extra · Cancellazione · Deposito · Protezione" su ogni pagina noleggio. Contenuti dai T&C attuali (PDF non ancora analizzato) | Medio | Bassa | **P1** |
| R12 | Fleet per modello e pacchetti | Eat Sleep Cycle (V) | Il ciclista esperto cerca il modello e il gruppo | Card per modello (Wilier Cento10 SL eTap, Diverge…) + pacchetti tematici (strade bianche, Chianti gravel, e-bike famiglia) | Medio | Media | **P1** |
| R13 | Percorsi rimandano a piattaforme esterne | Audit Gippo (V) | Contenuto SEO regalato a terzi | Pagine percorso sul sito (mappa, km, dislivello, bici consigliata + CTA noleggio), con link GPX a Komoot/RWGPS | Medio–Alto (SEO) | Media | **P1** |
| R14 | WhatsApp sulle pagine noleggio | Eat Sleep Cycle (V) | I turisti preferiscono la chat | Bottone WhatsApp Business (con orari) su noleggio e contatti | Medio | Bassa | **P1** |
| R15 | Trade-in e membership | REI (V) | Approvvigionamento dell'usato; fidelizzazione | Permuta usato → buono; "Gippo Club" (sconti officina, priorità noleggio) | Medio | Media | **P2** |
| R16 | Rete hotel e one-way | Papin Sport (V) | Distribuzione del noleggio dipendente dal sito | Programma partner per strutture ricettive (codice, consegna, commissione) | Medio–Alto | Media | **P2** |
| R17 | Contributo al territorio | Outside Sports (V) | Differenziazione del brand | Quota di ogni noleggio destinata alla cura dei percorsi locali | Basso–Medio | Bassa | **P2** |
| R18 | Distribuzione su Visit Tuscany e marketplace | Visit Tuscany, Freedome (V) | Visibilità ma rischio di canali disallineati | Mappare i canali attivi, allineare prezzi e contenuti, misurare la quota di prenotazioni dirette | Medio | Bassa | **P2** |

## 3. Cosa adottare, superare, evitare

**Adottare:** doppio ingresso in hero; booking date-first; fleet per modello; box "incluso/extra/policy"; recensioni in pagina; rent-to-buy.

**Superare i competitor:**
- Unire **noleggio → prova → acquisto → officina** in un'unica narrazione (nessuno lo fa).
- Prezzi visibili sia sul sito sia nel booking (quasi tutti i competitor li nascondono).
- Usato certificato da un dealer autorizzato con centro diagnosi Bosch/Yamaha/Brose.
- Bilinguismo IT/EN curato (errori di lingua in Lokki, Florence by Bike ed Eat Sleep Cycle).

**Evitare:**
- Due motori di booking o due flussi paralleli (Outside, Gippo oggi).
- FAQ copiate fra sedi o lingue (Eat Sleep Cycle).
- Placeholder e badge incoerenti (Cyclex gift card, rating "0 su 5" di Gippo).
- Ridurre il sito a una landing che rimanda altrove (Rutland Cycling).
- Copiare l'estetica di Canyon o Specialized (D-003).

## 4. Architettura proposta (PROPOSTA — richiede approvazione per D-002)

Evoluzione dell'IA attuale, non sostituzione:

```
Home
├── Noleggio                     (ex "Noleggio Biciclette")
│   ├── Bici da corsa & gravel  (linea Premium)
│   ├── E-bike & e-MTB
│   ├── Touring & famiglia
│   ├── Vespa                    (ex "Noleggio Vespe")
│   ├── Consegna in Toscana
│   └── Come funziona · FAQ · Condizioni
├── Negozio
│   ├── E-bike                   (modelli + test ride)
│   ├── Bici nuove per marca
│   ├── Usato & ex noleggio
│   └── Prova e compra
├── Officina                     (estratta da "Vendita & Assistenza")
├── Percorsi                     (pagine interne + GPX)
├── Chi siamo                    (Storia, Staff, Team Gippo — invariato)
└── Contatti                     (+ WhatsApp)
```

Implementazione: header e footer nativi Salient, sezioni WPBakery native, componenti riutilizzabili (card bici, card percorso, box policy) nel child theme solo dove WPBakery non basta.

## 5. Journey proposti

**Noleggio (turista):** Home → "Noleggia" → categoria → card modello (prezzo, incluso, taglie) → date (booking) → taglia, pedali, extra, ritiro o consegna → pagamento → conferma email/WhatsApp → promemoria pre-ritiro → post-noleggio: recensione + offerta "Prova e compra".

**Vendita (locale / acquirente e-bike):** Home → "Negozio" → E-bike → modello → "Prenota test ride" o "Noleggialo per un giorno" → visita in negozio → acquisto (credito noleggio applicato) → tagliando incluso in Officina.

**Usato:** Lista con filtri (tipo, taglia, prezzo) → scheda certificata → "Riserva / Chiedi informazioni" → visita.

## 6. Dipendenze, assunzioni, domande aperte

**Dipendenze**
- Capacità di Lokki: widget/iframe, sottodominio brandizzato, lingua forzata, campi custom (pedali, altezza), notifiche — **da verificare con Lokki**.
- Gestione stock usato/nuovo: dove vive oggi (gestionale? WooCommerce?) — sconosciuto.
- T&C noleggio (PDF) non ancora analizzati.

**Assunzioni**
- L'attuale WooCommerce (sort per prezzo presente su /usato) può supportare schede usato con prezzo.
- Il cliente gestisce già le prenotazioni Lokki (167 recensioni ne indicano un uso reale).

**Domande aperte per il cliente**
1. Che quota delle prenotazioni arriva da Lokki, dal form email, da telefono e da Visit Tuscany/marketplace?
2. È disposto a mostrare i prezzi dell'usato e del nuovo online?
3. Regola "Prova e compra": quale percentuale o tetto è sostenibile?
4. Il modello a noleggio è garantito (es. Specialized Diverge) o "equivalente" (Cube/BMC)?
5. Il fleet viene venduto a fine stagione?
6. Ci sono strutture ricettive partner già attive?
7. Quali tour guidati, se presenti, sono venduti direttamente?
