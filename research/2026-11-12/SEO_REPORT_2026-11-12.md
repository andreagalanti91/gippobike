# Gippo Bike — Report SEO (12/11/2026)

Fonti: crawl tecnico copia locale (199 URL) + controlli GET su produzione; analisi SERP/competitor su 26 keyword IT/EN;
lavoro fatto in locale (non ancora in produzione). Posizioni esatte, volumi e Core Web Vitals: **non misurati** (servono Search Console / strumento SEO).

## Situazione di partenza
- gippobike.com **non compare** nei risultati restituiti per nessuna delle 26 keyword (es. "noleggio bici siena", "bike rental tuscany").
- Chi vince: cctbikerental.com (pagine per città + costi consegna), e-bike-toscana.com (263 recensioni Google, FAQ), freedome.it (pagina per città/prodotto), marketplace lokki.rent e bikesbooking.com.

## Già fatto in locale (da portare in produzione)
| Area | Cosa |
|---|---|
| Pagine keyword | 8 pagine noleggio IT (hub, Toscana, Val d'Elsa, San Gimignano, Siena, Chianti, corsa, gravel, e-bike) + Vespa, negozio, e-bike vendita, storia, staff, team, contatti — tutte con versione EN |
| On-page | 1 H1 per pagina, risposta diretta 40–60 parole, title ≤60 / meta 140–155, prezzi reali in testo, FAQ, link interni hub↔satelliti |
| Dati strutturati | BikeStore/LocalBusiness su tutte le pagine, FAQPage automatico dalle FAQ |
| Multilingua | hreflang IT↔EN corretti su tutte le nuove pagine; **riparato** il collegamento rotto noleggio IT↔EN (bug presente anche in produzione) |
| UX / mobile | Design nuovo, accessibilità verificata a 1440/1024/375, barra "Prenota / Chiama" fissa su smartphone, campi ≥16px |
| Performance | Font Inter self-hosted (0 richieste a Google Fonts), URL di produzione rimossi dal DB locale |

## Da migliorare — in ordine di priorità

### P0 — Subito (blocca o diluisce il ranking)
1. **Pagine di test indicizzabili e in sitemap** (anche in produzione): /en/test/, /en/test-drive/, /en/prenota-noleggio/, /prenota-noleggio/, /product-option/, /5936-2/ (title vuoto), /noleggio-biciclette-2/. → noindex o eliminare + redirect 301 alla pagina giusta.
2. **292 pagine "allegato" indicizzabili** (una per immagine, ~30 parole): Yoast → *Media → reindirizza gli URL degli allegati all'allegato stesso* = sì.
3. **Google Business Profile**: è il primo risultato per "noleggio bici + città". Categorie (noleggio biciclette, negozio, officina), foto vere, orari, link alle pagine città, **raccolta recensioni sistematica** (link diretto dopo ogni noleggio). Il competitor principale ha 263 recensioni.
4. **NAP coerente**: il sito dice "Loc. Ponte dell'Armi 13A", una guida esterna "SP 541 Mensanello". Un solo indirizzo ovunque (sito, GBP, directory, Lokki).
5. **Bici usate tutte "Disponibile"**: 34 prodotti, nessuno venduto/esaurito. Le bici vendute vanno messe "esaurito" (o 410/redirect alla categoria) — altrimenti utenti delusi e pagine zombie.

### P1 — Contenuti e struttura (prossime 2–4 settimane)
6. **Home senza H1** e title di 75 caratteri. Sostituire la RevSlider con l'elemento *GB Immagine fullscreen* (H1 "Negozio e noleggio bici a Colle di Val d'Elsa"), title ≤60.
7. **Meta description mancanti sul 65% delle pagine** (129/199, soprattutto prodotti e vecchie pagine EN). Template Yoast per prodotti + descrizioni a mano per le pagine chiave.
8. **H1**: 49 pagine senza H1 e 19 con più di uno (vecchie pagine, prodotti, categorie). Le nuove pagine sono a posto; resta il legacy (percorsi, prenota, categorie prodotto).
9. **Title troppo corti**: 99 pagine sotto 30 caratteri (es. "Prenota - Gippo Bike"). Formula: *Cosa + Dove | Gippo Bike*.
10. **Doppioni e lingue miste**: /usato/ e /en/usato/ con lo stesso testo italiano; due pagine EN usato (/en/usato/ e /en/used-bicycles/); /en/prenota-noleggio/ in italiano; canonical EN che puntano a IT (/en/itineraries/…, /en/ebike/134410_d-17/). → unificare, tradurre o noindex.
11. **Schede prodotto (usato)**: niente prezzo visibile né schema Product/Offer → niente rich result. Mostrare il prezzo (o "prezzo su richiesta"), condizione (`itemCondition: UsedCondition`), taglia; slug corretti (es. "Armony Touring Elettrica" ha slug `specialized-turbo-levo-m-copy`).
12. **Pagine ancora da creare** dal piano: *Firenze consegna in hotel* (serve conferma costi/tempi), versioni EN di Vespa/tour; poi Volterra/Casole se i dati lo giustificano.
13. **Contenuti che fanno la differenza** (non inventabili, servono dal cliente): costi di consegna per zona (il competitor li pubblica), cauzione/cancellazione/pagamento, percorsi verificati Siena/Chianti/Firenze, foto vere delle bici a noleggio (l'hero attuale è una foto di gara pro, diritti da verificare), stato rivenditore ufficiale.

### P2 — Tecnico e performance
14. **Produzione**: sitemap e hreflang in `http://` mentre i canonical sono `https://`; robots.txt senza riga `Sitemap:`; redirect http→https→www in 2 salti; niente HSTS né cache header.
15. **Peso pagina in produzione**: 37 CSS + 33 JS (13 nel head), Google Fonts bloccante; immagine da 662 KB (1920×1920) sulla pagina noleggio, PNG da 449 KB; 8/19 immagini home senza width/height (CLS). → WebP/AVIF, dimensioni corrette, plugin cache, rimuovere plugin inutili (js_composer 5.4 inattivo, form plugin non usati: FormCraft, dhvc-form, fsq).
16. **Robots locale ≠ produzione**: in locale 120 archivi prodotto/tag/marchio sono noindex, in produzione no → decidere una regola (consigliato: noindex su tag e filtri, index su categorie e prodotti) e verificarla in Yoast prima del deploy.
17. **AI search**: aggiungere `/llms.txt` (chi siamo, servizi, zone, link a listino e pagine città); lasciare aperti OAI-SearchBot, PerplexityBot, Claude-SearchBot nel robots.

### P3 — Autorevolezza (continuo)
18. Profili coerenti su TripAdvisor, Komoot (collezione "Gippo Bike" con i percorsi), Strava club, Visit Tuscany / pro loco, portali hotel partner (link dai siti degli hotel serviti).
19. Una pagina "Percorsi" vera, una per percorso (distanza/dislivello da Komoot), linkata dalle pagine città: contenuto originale che i competitor non hanno.
20. Monitoraggio mensile: 20 query chiave su Google + ChatGPT/Perplexity (citati? chi sì?), Search Console (impressioni pagine città), recensioni GBP.

## Prossimo passo consigliato
Deploy in produzione delle pagine nuove (con backup) + i 5 punti P0, poi Search Console: invio sitemap e richiesta indicizzazione delle pagine città.
