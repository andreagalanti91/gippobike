# Keyword research via public autocomplete (Gippo Bike)

**Important:** autocomplete has no search volume. `times_seen` = number of distinct (source, query) requests in which the suggestion appeared. It is a rough popularity proxy only. Suggestions are not search volumes and do not prove demand.

## Method and coverage

- Requests sent: 2142 (ok 2142, errors 0). Google suggest (`suggestqueries`, hl per language, gl=it) and Bing suggest (`api.bing.com/osjson`, market it-IT / en-GB / de-DE / fr-FR / nl-NL).
- Per seed (template + place), both sources: seed alone and seed + space. This covers all seeds in all five languages.
- Letter expansion (seed + a–z): Google only, IT and EN only, on the core template (`noleggio bici <place>` and `bike rental <place>`), not on every template.
- Modifiers: Google only, on the core template. IT and EN use the full modifier list (26 each). DE, FR and NL use the first 10 modifiers only. This reduced scope is due to the request cap.
- Bing was not run with letter or modifier expansion. EN uses market en-GB only (no en-US).
- `language` = language group of the query that returned the suggestion. A suggestion may itself be in another language (for example English results inside Italian queries).
- Stopped sources: none (no captcha or repeated errors).

## Unique suggestions per language and source (case-insensitive, per language)

| Language | Google unique | Bing unique | Total unique rows (any source) |
|---|---|---|---|
| IT | 175 | 308 | 463 |
| EN | 282 | 262 | 524 |
| DE | 39 | 25 | 59 |
| FR | 18 | 87 | 103 |
| NL | 5 | 1 | 6 |
| **All** | 519 | 683 | 1155 |

## Top 25 suggestions by times_seen (all languages)

| # | Suggestion | Lang | times_seen | Source |
|---|---|---|---|---|
| 1 | noleggio bici da corsa | IT | 34 | bing |
| 2 | noleggio lungo termine bici elettriche | IT | 32 | bing |
| 3 | noleggio bici vicino al centro | IT | 30 | bing |
| 4 | noleggio bici elettriche costo | IT | 28 | bing |
| 5 | noleggio bici elettriche milano | IT | 27 | bing |
| 6 | noleggio bici lungo termine | IT | 26 | bing |
| 7 | colle di val d'elsa | IT | 24 | bing |
| 8 | gippo bike colle val d'elsa | IT | 24 | bing |
| 9 | noleggio furgoni colle di val d'elsa | IT | 24 | bing |
| 10 | rent a bike italy | EN | 22 | bing |
| 11 | colle di val d'elsa provincia | IT | 22 | bing |
| 12 | noleggio bici da corsa milano | IT | 22 | bing |
| 13 | noleggio bici elettriche bologna | IT | 22 | bing |
| 14 | noleggio bici elettriche roma | IT | 22 | bing |
| 15 | abc noleggio colle di val d'elsa | IT | 20 | bing |
| 16 | biciclette elettriche a noleggio | IT | 20 | bing |
| 17 | colle di val elsa | IT | 20 | bing |
| 18 | dove si trova colle di val d'elsa | IT | 20 | bing |
| 19 | noleggio bici elettrica costo | IT | 20 | bing |
| 20 | bici in val d'orcia | IT | 18 | bing |
| 21 | crete senesi in moto | IT | 18 | bing |
| 22 | noleggio bici elettriche favignana | IT | 18 | bing |
| 23 | noleggio bici val di fassa | IT | 18 | bing |
| 24 | circolo 2 colle di val d'elsa | IT | 16 | bing |
| 25 | colle di val d'elsa 53034 | IT | 16 | bing |

## Strongest places and products per language (sum of times_seen)

- **IT places:** colle di val d'elsa (301), florence (185), val d'orcia (173), tuscany (102), siena (98), chianti (93)
- **IT products:** bike (416), e-bike (384), shop/repair (148), tour (142), road (116), vespa (78)
- **EN places:** florence (306), tuscany (228), siena (217), san gimignano (116), chianti (105), volterra (34)
- **EN products:** bike (583), tour (231), e-bike (185), gravel (172), vespa (156), road (49)
- **DE places:** tuscany (36), florence (25), siena (16), san gimignano (10), chianti (8)
- **DE products:** tour (55), bike (54), e-bike (14), road (6), mtb (2)
- **FR places:** san gimignano (42), tuscany (34), florence (19), siena (18), chianti (12)
- **FR products:** e-bike (130), bike (83), road (20), tour (18)
- **NL places:** tuscany (8), siena (4)
- **NL products:** bike (8), road (4)

## Modifiers (unique suggestions containing each, all languages)

| Modifier | Total | IT | EN | DE | FR | NL |
|---|---|---|---|---|---|---|
| e-bike | 174 | 76 | 59 | 6 | 33 | 0 |
| near | 55 | 15 | 35 | 5 | 0 | 0 |
| gravel | 48 | 13 | 35 | 0 | 0 | 0 |
| road | 42 | 17 | 12 | 3 | 8 | 2 |
| routes/itineraries | 34 | 9 | 5 | 0 | 20 | 0 |
| price | 18 | 10 | 6 | 0 | 2 | 0 |
| guided | 13 | 2 | 10 | 1 | 0 | 0 |
| wine | 10 | 4 | 6 | 0 | 0 | 0 |
| reviews | 6 | 2 | 4 | 0 | 0 | 0 |
| best | 6 | 2 | 4 | 0 | 0 | 0 |
| family/kids | 3 | 1 | 1 | 1 | 0 | 0 |
| mtb | 2 | 2 | 0 | 0 | 0 | 0 |
| eroica | 1 | 1 | 0 | 0 | 0 | 0 |
| daily | 1 | 0 | 0 | 0 | 1 | 0 |

## Intent mix (unique suggestions)

- IT: transactional-rental 182, price 10, info-route 2, tour/guided 53, shop/repair 56, other 160
- EN: transactional-rental 328, price 6, info-route 5, tour/guided 82, shop/repair 4, other 99
- DE: transactional-rental 31, tour/guided 26, other 2
- FR: transactional-rental 57, price 2, info-route 15, tour/guided 9, other 20
- NL: transactional-rental 6

## Seeds that returned NOTHING (base query, both sources empty = very low demand signal)

- **IT** (22 of 144 seeds empty on both sources; 71 empty on Google): noleggio gravel monteriggioni; noleggio gravel volterra; noleggio gravel poggibonsi; noleggio vespa monteriggioni; bici elettriche monteriggioni; bici elettriche volterra; bici elettriche poggibonsi; negozio bici monteriggioni; officina bici chianti; officina bici val d'elsa; officina bici monteriggioni; officina bici volterra; officina bici poggibonsi; officina bici toscana; riparazione bici chianti; riparazione bici monteriggioni; riparazione bici volterra; riparazione bici toscana; bici usate chianti; bici usate val d'elsa; bici usate monteriggioni; bici usate volterra
- **EN** (5 of 63 seeds empty on both sources; 15 empty on Google): e-bike rental volterra; e-bike rental monteriggioni; bike tour monteriggioni; cycling monteriggioni; vespa rental monteriggioni
- **DE** (4 of 25 seeds empty on both sources; 6 empty on Google): e-bike verleih chianti; rennrad mieten chianti; e-bike mieten chianti; e-bike mieten siena
- **FR** (0 of 15 seeds empty on both sources; 5 empty on Google): none
- **NL** (4 of 9 seeds empty on both sources; 4 empty on Google): fiets huren chianti; e-bike huren chianti; e-bike huren siena; racefiets huren chianti

## Caveats

- Autocomplete reflects query-completion suggestions, which are biased by personalisation, location and language settings. It is not representative of search volume or conversion.
- The rule-based classifiers (place, product, intent, modifiers) use keyword matching on the suggestion text. Items may be misclassified, for example a rental query with "tour" in it lands in tour/guided.
- `source` = google+bing when both sources returned the same text for the same language.

Files: `/private/tmp/claude-501/-Users-andreagalanti-Local-Sites-gippobike-app/d52d4693-ed0f-46f9-b5a9-434976dd47af/scratchpad/kw_autocomplete.csv` (1155 rows)
