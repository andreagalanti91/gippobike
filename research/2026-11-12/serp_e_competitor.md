# Gippo Bike: SERP and competitor map (Siena / Chianti / Tuscany bike rental)

Date of research: 2026-11-12
Method and limits:
- Search: `WebSearch` tool, standard mode, one query per keyword (26 queries: 18 IT, 8 EN). The tool does not expose the search engine name, the ordering or the rank position of each link, so "top domains" below are the links in the order returned (approximate, not verified Google positions).
- The tool returns no SERP features. Map pack, FAQ rich results and "People also ask" are **not retrieved** for any keyword. The FAQ questions in section 6 come from on-page FAQs of competitor sites, not from Google PAA.
- Pages fetched with `WebFetch` (cached 15 min). lokki.rent returned HTTP 429 on two fetches, so its data below comes from search snippets only.
- No search volumes, keyword difficulty or schema were measured. "Difficulty" in section 5 is a guess from the SERP composition.
- No form was submitted. Production pages were read only.

---

## 1. Gippo Bike presence in the 26 SERPs

| Keyword | Gippo domain (gippobike.com) in returned links | Top domains returned (approx. order) | Notes |
|---|---|---|---|
| noleggio bici siena | No | lanazione.it (news), bikesbooking.com, visittuscany.com, lokki.rent, touringclub.it, komoot, travelocity/expedia (tours), airbnb | Gippo absent |
| noleggio bici san gimignano | No | freedome.it (x2), expedia/ebookers (tours), visittuscany.com, lokki.rent, trip.com, touringclub.it | Gippo absent |
| noleggio bici toscana | No | turismo.lucca.it (PDF), musement.com, lokki.rent (smileandride, sieci), freedome.it, summerinitaly.com, e-bike-toscana.com, winedering | Gippo absent |
| noleggio e-bike toscana | No | freedome.it, emmavillas.com (PDF), winedering, lokki.rent, holidoit.com, advcollective.com, trip.com, e-bike-toscana.com | Gippo absent |
| noleggio e-bike siena | No | freedome.it (Chianciano, Montepulciano), visittuscany.com, holidoit.com, lokki.rent (E-Bike Siena), bikesbooking.com, winedering, lokalee.app | Gippo absent |
| noleggio bici chianti | No | freedome.it, visittuscany.com, winedering, lokki.rent (Yep Bike), lokalee.app, holidoit.com, bookyourrent.com, e-bike-toscana.com, headout | Gippo absent |
| noleggio bici da corsa toscana | No | lokki.rent (Smile & Ride), turismo.lucca.it, summerinitaly.com, advcollective.com, freedome.it, discovertuscany.com, e-bike-toscana.com | Gippo absent |
| noleggio gravel toscana | No | visittuscany.com, lokki.rent (Smile & Ride), winedering, lanazione.it, e-bike-toscana.com, komoot, quotidiano.net | Gippo absent |
| noleggio bici firenze consegna hotel | No | bikesbooking.com, telepass (bike sharing), freedome.it, visittuscany.com, visitflorence.it, musement.com, reidsitaly.com | Gippo absent |
| noleggio bici colle di val d'elsa | No (no gippobike.com URL in links) | lokki.rent (dedicated Colle page), visittuscany.com (x2), freedome.it, siviaggia.it, lokki.rent (Spidibike), bikesbooking.com, bookyourrent.com, wetravel.com (Tuscany Quintessence) | Gippo not in links. A summary line from the tool mentioned "Gippo Bike Rental" at Ponte dell'Armi, but no gippobike URL was returned. Treat as unverified |
| noleggio bici poggibonsi | No | free2move.com (cars), lanazione.it, wetravel.com, komoot, visittuscany.com, freedome.it, turismo.lucca.it | No bike shop in Poggibonsi found |
| noleggio bici volterra | No | visittuscany.com, emmavillas.com (PDF), lokki.rent, freedome.it, holidoit.com, komoot, bed & bike (volagratis) | Gippo absent |
| noleggio vespa siena | No | freedome.it (Pienza), bikesbooking.com, advcollective.com, matrimonio.com, riderly.com, musement.com, nattivus.com, kimkim.com, moneyside.app | Gippo absent. Production has /noleggio-vespe/ (see section 3) |
| negozio bici siena | No | promoqui.it (Lombardo Bici Siena, Via Aretina 35), doveconviene.it, trekbikes.com (Firenze), unisi.it (Bicincittà e-bike), visittuscany.com, bikesbooking.com | Gippo absent |
| negozio bici colle di val d'elsa | No | decathlon.it (Colle, Loc. Belvedere), doveconviene.it (many chain stores), summerinitaly.com, visittuscany.com | Gippo absent. A summary line gave Gippo's address and phone, but no gippobike URL was returned |
| officina bici siena | No | lanazione.it (theft news), subito.it, decathlon.it, bikesbooking.com, visittuscany.com, trekbikes.com (Firenze) | Gippo absent. D.F. Bike is named in text as a Siena bike centre |
| bici usate siena | No | subito.it (several), lanazione.it, decathlon.it (second-hand), mtb-forum.it, bikesbooking.com, moto.it | Gippo absent. Production has /usato/ (see section 3) |
| specialized siena | No | eBay sellers (self-described "rivenditore ufficiale Specialized", location not confirmed), trustpilot (Taddei Store), specialized.com IT page, autoscout24 (car dealers), subito.it (private seller), orbea.com dealers, trekbikes | **No confirmed Specialized dealer in Siena found** |
| bike rental tuscany (EN) | No | summerinitaly.com (several), toscana-forum.de, advcollective.com (Florence by Bike), freedome.it, aaa.com TripCanvas, theabroadguide.com, e-bike-toscana.com, riderly.com, lokalee.app | Gippo absent |
| bike rental siena (EN) | No (third-party listing only) | community.ricksteves.com, freedome.it, bikesbooking.com, summerinitaly.com, aboutsiena.com, **yumping.com (listing "Gippo Bike")**, ebiketravel.it, cctbikerental.com, visittuscany.com, lokki.rent, e-bike-toscana.com | Gippo appears only via a yumping.com listing, not on gippobike.com |
| e-bike rental tuscany (EN) | No | summerinitaly.com, aaa.com, freedome.it, magpie.travel, theabroadguide.com, somewheregood.com, trip.com, e-bike-toscana.com, travel-buddies.com, lokalee.app | Gippo absent |
| road bike rental tuscany (EN) | No | summerinitaly.com (Castelfiorentino, Land Hill, Gaiole), cctbikerental.com, advcollective.com, e-bike-toscana.com, discoverfrance.com | Gippo absent |
| bike rental san gimignano (EN) | No | freedome.it, cctbikerental.com, lokalee.app, lokki.rent, visittuscany.com, expedia/travelocity (tours), mytour.eu, italybikehotels.com | Gippo absent |
| bike rental chianti (EN) | No | magpie.travel, freedome.it, visittuscany.com, summerinitaly.com (Gaiole), cctbikerental.com, trip.com, lokalee.app, bookyourrent.com, expedia, e-bike-toscana.com | Gippo absent |
| gravel bike rental tuscany (EN) | No | e-bike-toscana.com, cctbikerental.com (x several), lokalee.app, biketours.com, 57hours.com, italybikehotels.com, visittuscany.com | Gippo absent |
| bike rental florence hotel delivery (EN) | No | bikesbooking.com, cctbikerental.com, dyvarcity.com (Padbike), tripaligner (Tuscany.Bike), fhhotelgroup.it, riderly.com (motorbike), lokalee.app, travelarbitrage.net | Gippo absent |

Summary: gippobike.com did not appear in any of the 26 returned link sets. Its only SERP trace is a third-party yumping.com listing for "bike rental siena". Positions and SERP features are not retrieved.

---

## 2. Competitors (6-8 strongest direct rivals)

| # | Domain | Area / type | Landing pages seen (URLs) | Page patterns | Languages | Strength | Weakness |
|---|---|---|---|---|---|---|---|
| 1 | cctbikerental.com | Tuscany-wide rental with delivery, Chianti/Siena/Florence/San Gimignano | /rentals/san-gimignano-bike-rentals ; /rentals/gravel-bike-rentals-tuscany ; /rentals/siena-roma-via-francigena-bike-rentals ; /location/tuscany-bike-rentals/ ; /?p=... pages for Greve, Florence, Siena | Prices per 2 and 14 days (table). Delivery-fee grid by town (Poggibonsi/Colle €50; San Gimignano/Siena/Castellina/Radda €100; Gaiole/Greve/Panzano €150). 4-step booking calendar. FAQ & CCT Info page. Delivery hours listed. | EN (IT pages present in part) | Best-in-class per-town pages with delivery matrix and transparent prices. Gravel page with Wilier Jareen. | Booking needs 3 days' notice and 2-day minimum. Conflicting minimums across pages. No reviews on the page. |
| 2 | lokki.rent | Marketplace of rental points (Siena, Colle, San Gimignano, Florence, Pisa, Gaiole) | /it/noleggio/colle-di-val-delsa/bici ; /it/noleggio/sienne/bici ; /en/rental/san-gimignano/bicycle ; /it/noleggio/sieci/bici ; /it/punto-noleggio/e-bike-toscana ; /it/punto-noleggio/smileandride ; /en/rental-point/ebikesiena | City pages titled "Noleggiare una bici a [città]: tariffe, percorsi e consigli" (price ranges, tips). Product pages per bike size. Ratings shown (snippet: 4.9/5, 50+ reviews, Google and Tripadvisor). Average prices from its booking data: Siena bike 18-57/day, e-bike ~39/day. | IT, EN, DE | Owns city-level pages for Colle di Val d'Elsa and Siena, which are Gippo's core keywords. Many rental points means broad coverage. | Marketplace with thin, templated city copy. Fetches returned HTTP 429 (not reviewed in full). |
| 3 | e-bike-toscana.com | Pian dei Mori (Sovicille, near Siena). Rental, tours, workshop, sales | / (EN and IT); /en/content/11-tuscany-bike-rental ; /en/content/19-tuscany-gravel-bikes-rental ; /en/content/22-road-bikes-rental-in-tuscany | H1 "Tuscany and Chianti Bike Tours & E-Bike Rental". FAQ (helmets, children's sizes 135/150 cm, one-way routes, deposit and cancellation). Delivery to accommodation. 263 Google reviews with a verified badge. No prices on the home page. Road bike Cannondale CAAD Optimo 40 EUR/day (snippet). Gravel 50 EUR/day or 280 EUR/week (listing), an older page says 20/110. | IT, EN | Closest direct rival near Siena: e-bike, MTB, gravel, road; workshop and sales; many reviews; GPX tours. Category pages per bike type. | Prices are not on the home page. Gravel price varies between pages. |
| 4 | freedome.it | Multi-town rental and tours (San Gimignano, Certaldo, Chianciano, Montepulciano, Pienza, Florence, Chianti, Val d'Orcia) | /attivita/noleggio-ebike-giornaliero-san-gimignano/ ; /attivita/noleggio-ebike-certaldo-valdelsa/ ; /attivita/noleggio-ebike-chianciano-terme/ ; /attivita/noleggio-vespa-pienza/ ; /noleggio-e-bike/toscana/ ; /bike-e-bike/toscana/ | Template per town: H1 keyword, 8 H3 sections (what is included, how it works, where you will be, FAQ). FAQ block on each page. From 50 EUR/9h e-bike. Cancellation 24h. Booking as a request (guide replies within 48h, payment pre-authorised). Vespa Pienza page. | IT, EN | Strongest templated SEO structure in the area: one page per town and per product, with FAQ. Covers Vespa and e-bike. | Request-based booking adds friction. No ratings on the page. Ships many thin pages. |
| 5 | bikesbooking.com | Aggregator (claims 942 suppliers) | /it/rent-a-bicycle-in-Siena/ ; /it/rent-a-bicycle-in-Florence/ ; /it/rent-a-motorcycle-in-Siena/ | Title "Noleggio Biciclette a Siena da €3/giorno", H1 "Top 5 migliori noleggi di biciclette a Siena". Price bands per day (3-10 low season; 15-25 standard; 30-50 road/e-bike). Long editorial sections. | Many languages | Ranks for every "noleggio bici [città]" query. Trusted brand, wide listing, editorial text. | Aggregator, not a shop. Ratings are not numeric on the page. Competes on the same queries Gippo targets. |
| 6 | yepbike / bookyourrent.com | San Casciano in Val di Pesa (Chianti) | /en/rental/san-gimignano ; /en/rental/san-casciano-val-di-pesa ; /en/rental/san-casciano-val-di-pesa/yep-bike | e-trekking 55 EUR/day (snippet); private guided tours (4h). 18 reviews on bookyourrent. | IT, EN | Chianti-specific, clear price, reviews. | Small review count. Listed under lokki.rent's Yep Bike point as well. |
| 7 | Tuscany Bike Rental / Tuscany Bicycle (Gaiole in Chianti) | Chianti (Gaiole) | summerinitaly.com/guide/tuscany-e-bike-rental (single listing, Via Roma 82) ; tuscanybicycle (tripaligner) | E-bike by hour, half day, day, multi-day; guided tours from 100 GBP (half day, snippet). Gravel with door-to-door hotel delivery (snippet). | EN | Chianti delivery positioning. | Little on-site data. Prices not visible in the fetched page. |
| 8 | Florence hotel delivery operators: Padbike (dyvarcity), Tuscany.Bike, Florence by Bike (lokki/advcollective), CCT (depot in Chianti) | Florence | dyvarcity.com/experiences/e-bike-rental-in-florence-with-home-delivery ; tripaligner Tuscany.Bike ; app.advcollective.com/local-experts/1-day-rental | Hotel delivery and pick-up included (listing claims). Van delivery for e-MTB (Padbike). | EN | Clear "delivery to hotel" value proposition, which Gippo also has. | Several delivery claims differ between listings. |

Additional rivals: Visit Tuscany (visittuscany.com) and Holidoit / Adventure Collective / Expedia / Travelocity / Trip.com are OTA or tour sellers. They rank on most "tour" and "e-bike tour" queries. Their listings often exclude the rental, which creates an opening for rental-only pages.

---

## 3. Gippo Bike current state (production site, read-only)

Production pages found and read:
- Home (EN and IT). Title: "Gippo Bike - Negozio e Noleggio di biciclette a Colle di Val d'Elsa, Siena". Banner "CYCLE THROUGH TUSCANY" and "SINCE 1985". Sections: Usato, Noleggia la tua bici, Provata l'e-bike?, Percorsi, Il Negozio, Noleggia la tua Vespa. Address "Loc. Ponte dell'Armi 13A, 53034 Colle di Val d'Elsa (SI)". Phone 0577 904405. Email gippo@gippobike.it. No opening hours.
- /noleggio-biciclette/ (IT). Title: "Noleggio biciclette Siena San Gimignano Casole d'elsa Volterra Monteriggioni - Gippo Bike". One page for all towns. Bike categories as H1 (Corsa, Corsa Di2, Gravel, Gravel Elettrica, Touring, MTB Elettrica, Tandem, etc.). Prices per day/week, e.g. Wilier Cento10 SL 60/340; Wilier GTR Team Di2 50/280; Wilier GTR Team 40/220; Specialized Diverge Carbon (gravel) 45/250; XP Allroad e-gravel 60/340; Haibike ALL MTN 1 e-MTB 60/340; Touring Cube One 20/110; Cube Aim SLX MTB 25/140. Daily rental 9:00-19:00. Helmet and puncture kit included. Delivery "on request". Booking form (name, contact, dates, bike type, height, pedals, sex, delivery location), plus email and a quick-booking link. Delivery areas: "All of Tuscany, including Chianti, San Gimignano, Siena, Volterra, Monteriggioni, Colle Val d'Elsa, Casole d'Elsa, and beyond". No FAQ, no reviews found on this page. Language switcher shows only Italiano.
- /noleggio-vespe/ (IT). Title "Noleggio Vespe - Gippo Bike". Vespa 125cc 70 EUR/day, 370 EUR/week, helmet included, fuel not. Pick-up at shop or delivery for an extra fee. Booking form present.
- /ebike/ (IT). Title "E-Bike - Gippo Bike". Brand logos only (Fantic, Specialized, Haibike, Husqvarna, Cube, Triestina). No models or prices. Test ride CTA. No FAQ.
- /en/ (EN). Exists and is in English. H1 area "Bike Rental in Tuscany". Title: "Gippo Bike, bike shop in Colle di Val d'Elsa, Siena, bike rental in Siena area, E-bike shop, bike repair, bike assistence, bike clothing".
- /usato/ (used bikes), /vendita-assistenza/ (sales, service, maintenance), /percorsi/ (routes; Komoot, RideWithGPS and Bikemap links).

Production sitemap (http://www.gippobike.com/page-sitemap.xml) includes these relevant URLs (not all fetched):
- /noleggio-biciclette/ and /noleggio-biciclette-2/ (IT duplicate candidate)
- /noleggio-vespe/ ; /en/vespa-rental/
- /en/gippo-bike-bike-rentals-vespa-rental-siena-san-gimignano-2/ ; /en/gippo-bike-bike-rental-vespa-rental-colle-val-delsa-siena-san-gimignano/ (English location-keyword slugs, not fetched)
- /en/bike-rental-quick-booking/ ; /prenota-noleggio/ ; /en/prenota-noleggio/
- /en/test/ ; /en/test-drive/ ; /en/test-drive/ : these look like test or leftover pages and should be checked for indexation
- /5936-2/ ; /product-option/ : look like technical or leftover URLs
- /ebike/ ; /en/ebike/ ; /en/used-bicycles/ ; /usato/ ; /en/sales-and-repairs/ ; /vendita-assistenza/ ; /en/history/ ; /la-storia-gippo-bike/ ; /team-gippo/ ; /en/team-gippo/ ; /staff/ ; /contatti/ ; /en/contact/ ; /percorsi/ ; /en/itineraries/
- NOT in production: /noleggio-bici-toscana/ and /noleggio-bici-san-gimignano/ (local pages 6051/6052 per CLAUDE.md). Consistent with local-only status.

### Keyword coverage gap table

| Keyword cluster | Dedicated page on production? | Current title / H1 | Gap |
|---|---|---|---|
| noleggio bici siena | No. Siena is only a list item on /noleggio-biciclette/ | Shared title lists 5 towns | No Siena page; title dilutes focus |
| noleggio bici san gimignano | No | Shared title | No page, no tour / e-bike SG content |
| noleggio bici toscana | Partial. /noleggio-biciclette/ covers "All of Tuscany" in body | "Noleggio biciclette Siena San Gimignano..." | Title lacks "Toscana"; no delivery fee info |
| noleggio e-bike toscana / siena | No dedicated page. /ebike/ has brand logos, no models or prices | "E-Bike - Gippo Bike" | Thin page, no e-bike prices (competitors show them) |
| noleggio bici chianti | No | None | Chianti is named as delivery area only |
| noleggio bici da corsa toscana | No. Road bikes are a category on /noleggio-biciclette/ | Category heading "Corsa" | Good inventory (Wilier Cento10 SL 60/day), but no page |
| noleggio gravel toscana | No. "Gravel" is a category label, no gravel page | Category H1 only | Gravel Specialized Diverge 45/day exists; no page targets it |
| noleggio bici firenze consegna hotel | No. Florence not mentioned | None | Hotel delivery offer is generic ("on request") |
| noleggio bici colle di val d'elsa | Home page targets it ("Negozio e Noleggio... Colle di Val d'Elsa") | Home title | Strong local base; no rental-specific Colle page |
| noleggio bici poggibonsi | No | None | No mention |
| noleggio bici volterra | No. Volterra is in the title and the delivery list only | Shared title | No page |
| noleggio vespa siena | Yes: /noleggio-vespe/ (Vespa 125cc 70/day) | "Noleggio Vespe - Gippo Bike" | Title lacks "Siena"; no FAQ |
| negozio bici siena / colle | Home and /vendita-assistenza/ partly | Home title | No page with "negozio bici Siena" intent |
| officina bici siena | /vendita-assistenza/ (sales, service, maintenance) | Not reviewed in detail | Repair and workshop page does not target "officina bici Siena" |
| bici usate siena | /usato/ | Not reviewed in detail | Used-bike listings are sparse (not verified) |
| specialized siena | Specialized brand shown on /ebike/ and in rental (Diverge, Sirrus) | None | Dealer status not verified on production; no page |
| EN keywords (bike rental tuscany / siena / san gimignano / chianti / gravel / road / e-bike) | /en/ exists (title in EN). EN location slugs exist in sitemap | EN home title | Only the home is in English on the fetched evidence; rental and category pages not verified in EN |

### Other observations (production)
- Address mismatch: the production site says Loc. Ponte dell'Armi 13A. A third-party guide (returned by search) says "SP 541 Mensanello". Confirm NAP (name, address, phone) across Google Business Profile, site and directories before any local SEO work.
- Phone on production: 0577 904405. Check that the same number appears on any listing sites.
- Competitors publish a price grid or delivery-fee table; Gippo's delivery is "on request" and no fee is stated.
- No FAQ and no reviews on /noleggio-biciclette/ or /noleggio-vespe/.
- Schema.org markup was not verified (WebFetch returns text, not JSON-LD).

---

## 4. Per-keyword verdict: where Gippo ranks

| Keyword | Gippo rank | Evidence |
|---|---|---|
| All 18 IT and 8 EN keywords except the Colle/Vespa/Siena-shop cases | Absent from returned links (top ~10) | gippobike.com not returned |
| noleggio bici colle di val d'elsa | Absent in returned links | Gippo home is the local base but not in the returned top set |
| bike rental siena (EN) | Not on gippobike.com. Third-party listing at yumping.com | Only trace |
| noleggio vespa siena | Absent in returned links | /noleggio-vespe/ exists on production |
| bici usate siena | Absent | /usato/ exists |
| specialized siena | Absent | no dealer confirmed |

Positions, SERP features and PAA: **not retrieved**.

---

## 5. Keyword clusters with best opportunity (guesses, not measured)

Difficulty is a qualitative guess from who holds the SERP. No volumes were retrieved.

| # | Cluster (keywords) | Intent | Difficulty (guess) | Who ranks (returned) | Why Gippo has an angle |
|---|---|---|---|---|---|
| 1 | noleggio bici / e-bike colle di val d'elsa, poggibonsi, monteriggioni | Local, transactional | Low-medium | lokki.rent (Colle page), visittuscany, freedome, bikesbooking, wetravel | Gippo is physically in Colle. Home already targets it. Needs a dedicated Colle rental page with prices and address |
| 2 | noleggio bici san gimignano | Local, transactional | Medium | freedome (template page), cctbikerental (delivery grid), lokki, tour OTAs | Gippo delivers to SG per its title. No page. Freedome's FAQ template is a model |
| 3 | noleggio bici siena / bike rental siena / e-bike siena | Local, transactional, high volume | High | bikesbooking, lokki, e-bike-toscana, cctbikerental, visittuscany, lanazione | Head term is contested. Long-tail "noleggio e-bike siena con consegna" is more winnable |
| 4 | noleggio bici chianti / bike rental chianti | Transactional, mid-volume | Medium | freedome, yep bike (bookyourrent), cctbikerental, Tuscany Bike Rental (Gaiole), tour OTAs | Gippo delivers to Chianti per title. Needs a Chianti page with delivery fee |
| 5 | noleggio gravel toscana / gravel bike rental tuscany | Transactional + informational | Medium | cctbikerental (Wilier Jareen, free delivery), e-bike-toscana, Tuscany Bicycle, biketours, 57hours | Gippo has a gravel bike (Specialized Diverge 45/day, e-gravel 60/day) with no gravel page. Good fit with the "Toscana gravel" trend (Regione presents Tuscany as gravel capital, per search snippet) |
| 6 | noleggio bici da corsa / road bike rental tuscany | Transactional | Medium | summerinitaly directory, cctbikerental, e-bike-toscana (Cannondale 40/day), lokki (Smile & Ride), advcollective | Gippo road range (Wilier Cento10 SL 60/day, GTR 40-50/day) is strong. No page |
| 7 | e-bike rental tuscany / noleggio e-bike toscana | Transactional, broad | High | freedome, lokki, summerinitaly, aaa.com, e-bike-toscana, holidoit | Too broad. Target the local sub-clusters (1-4) instead |
| 8 | firenze hotel delivery / consegna bici hotel toscana | Transactional + service | Medium-high | bikesbooking, cctbikerental, Padbike, Tuscany.Bike, Florence by Bike | Gippo's delivery across Tuscany is a USP if the fee is published. Florence itself is outside Gippo's base (~50 km) |
| 9 | negozio / officina bici colle di val d'elsa, negozio bici siena, officina bici siena | Local, transactional (service) | Low | decathlon (Colle), D.F. Bike (Siena, named), Lombardo Bici Siena (Via Aretina), e-bike-toscana (workshop) | Gippo's homepage already states sales, service and maintenance. Few specialists rank. Gap for a dedicated "officina" page |
| 10 | bici usate siena / usato toscana; noleggio vespa siena (guided and self-drive) | Transactional (used, Vespa) | Low (used) / Medium (Vespa) | used: subito.it, mtb-forum; Vespa: freedome (Pienza), tour operators (musement, visittuscany), bikesbooking | Gippo has /usato/ and /noleggio-vespe/ (70/day, helmet included). Vespa self-drive from Siena is thin in the returned results |

Notes on the lower-priority keywords:
- noleggio bici volterra, noleggio bici poggibonsi: low volume. Volterra competitors: freedome, visittuscany tours, emmavillas (private villa delivery). Poggibonsi: no bike shop found in results.
- specialized siena: no dealer confirmed in Siena. Check Specialized's dealer locator (specialized.com/it) and Gippo's brand status before any Specialized-focused copy.

---

## 6. Recurring "People also ask"-style questions

Google PAA was **not retrieved**. The questions below come from on-page FAQs and question headings of competitor sites. They are repeated across sites, which makes them good candidates for FAQ copy on Gippo pages.

From freedome.it FAQ blocks:
- Come funziona in caso di maltempo? (What happens if the weather is bad?)
- Se cancello la prenotazione, posso ottenere il rimborso completo? (Can I get a full refund if I cancel?)
- Quali metodi di pagamento accettate? (Which payment methods do you accept?)

From bikesbooking.com headings:
- Di cosa hai bisogno per noleggiare una bici a Siena? (What do I need to rent a bike in Siena?)
- Quale assicurazione è inclusa nella mia bicicletta a noleggio? (What insurance is included with the rental bike?)
- Quanto costa noleggiare una bici a Siena? (How much does a bike rental cost in Siena?)
- Quando prenotare? Qual è la stagione migliore? (When should I book? What is the best season?)

From e-bike-toscana.com FAQ:
- Are helmets included? (Included and recommended, not mandatory.)
- What height is needed for children's and adult bikes? (Children 135 cm, adults 150 cm.)
- Can routes be one-way? (Yes.)
- What is the deposit and cancellation policy?

From lokki.rent (snippet): Is a licence needed? Standard and pedal-assist e-bikes need no licence, registration or insurance in Italy. Shops set minimum age (usually 16 or 18) and ask for photo ID.

Gippo Bike (production) has no FAQ block on rental pages. This is a clear gap.

---

## 7. Suggested priorities for Gippo (for the SEO plan; no changes made)

1. Create dedicated IT and EN pages for: Colle di Val d'Elsa rental (cluster 1), San Gimignano (2), Chianti (4), gravel (5), road (6). Each with prices, delivery fee grid, FAQ and booking CTA. Use the native WPBakery shortcodes described in CLAUDE.md.
2. Publish a delivery fee grid by town (competitors do; CCT's grid is the benchmark). Verify Gippo's real fees first, do not invent them.
3. Split the shared title on /noleggio-biciclette/ into per-town intents, or keep it as a hub that links to the new pages.
4. Add FAQ blocks to /noleggio-biciclette/ and /noleggio-vespe/ (Freedome-style).
5. Add prices to /ebike/.
6. Confirm NAP (address, phone) across site, Google Business Profile and directories (address mismatch noted above).
7. Check whether /en/test/ and /en/test-drive/ are indexed; noindex or remove if they are test pages.
8. Verify Specialized dealer status before any Specialized-focused page.
9. Schema.org (LocalBusiness, Product, FAQPage) was not verified. Check it in the page source before writing new markup.

---

## 8. Sources used (URLs read or returned)

Gippo production (WebFetch): https://www.gippobike.com/ ; https://www.gippobike.com/noleggio-biciclette/ ; https://www.gippobike.com/noleggio-vespe/ ; https://www.gippobike.com/ebike/ ; https://www.gippobike.com/en/ ; http://www.gippobike.com/page-sitemap.xml

Competitors (WebFetch): https://www.cctbikerental.com/rentals/san-gimignano-bike-rentals ; https://e-bike-toscana.com/en/ ; https://freedome.it/attivita/noleggio-ebike-giornaliero-san-gimignano/ ; https://bikesbooking.com/it/rent-a-bicycle-in-Siena/ ; https://www.summerinitaly.com/guide/tuscany-e-bike-rental
Blocked (HTTP 429): https://www.lokki.rent/it/noleggio/colle-di-val-delsa/bici ; https://www.lokki.rent/en/rental/sienne/bicycle

Search-only (snippets, WebSearch): the 26 keyword queries listed in section 1. Result domains are as listed there.
