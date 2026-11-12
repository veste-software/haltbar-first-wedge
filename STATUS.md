# Haltbar (first wedge)

**Stage:** killed · **Platform:** web · **Score:** 5/5 · **Spend:** $0.58

Astro site plus a small app. Users upload the order file from Amazon's own data export (or connect via the portability API once allowlisted). They then see each item's 2-year statutory warranty and return deadlines and recall matches from the EU Safety Gate. At 6, 12 and 24 months they get an e-mail asking 'still working? yes / problem / broken'. Product pages appear only after 10 or more verified reports. Segment: Amazon.de buyers of chargers, power banks, headphones and small kitchen appliances, which are cheap, short-lived and often recalled. This is the first wedge of a larger bet, "Haltbar": A free warranty-and-recall tracker for Amazon.de shoppers that imports their orders with their consent and later asks 'is it still working?', turning the answers into purchase-verified durability pages for products. Build only the wedge, and keep the data model and the pages ready for the loop that makes it grow: Every owner who answers 'still working?' adds a dated, purchase-verified point to the product's durability curve, which ranks for 'erfahrungen' and 'defekt' searches and brings shoppers who connect their own orders.

**Why now:** standing need. Window: Amazon's Data Portability API gives authorised third parties consented access to EU customers' data, including an order scope. Fakespot's users are still searching ('fakespot alternative 2026' in autocomplete). EU consumer rules on reviews are tightening (a Digital Fairness Act is reported, not confirmed).

## Needs you

Nothing right now.

## Recommendation

None yet. The Growth role gives one after launch.

## Metrics

No real numbers yet. Fill in `metrics.json` (Search Console, analytics, Stripe); agents never invent them.

## Target queries

- amazon fake bewertungen erkennen
- fake bewertungen erkennen
- amazon bewertungen fake check
- gewährleistung amazon wie lange
- gewährleistung amazon geltend machen
- fakespot alternative
- amazon fake review checker
- rückruf amazon aktuell
- langlebige externe festplatte

## Alternatives found

- Amazon customer reviews (partial): Written at delivery time and gamed; the 2026 lawsuit lists paid verified-purchase reviews at $30 each; no durability data
- Fakespot (Mozilla) (partial): Shut down on 1 July 2025 because it did not fit a model Mozilla could sustain

## Links

- Repo: https://github.com/veste-software/haltbar-first-wedge
- Preview (GitHub Pages, builds from main): https://veste-software.github.io/haltbar-first-wedge/

## History

- 2026-11-12 13:44 · scouted · found by manual
- 2026-11-12 13:44 · scouted · ranked first in the daily pool (aggregate 2 of 5 by 3 independent rankers, including a Big-bet bonus of 0.3); the studio builds the day's best candidate whatever its score, and the prototype is how it is judged
- 2026-11-12 20:47 · killed · rejected by the product lead: Nobody pays: the product is free to shoppers and earns only a ~3% Amazon affiliate commission on replacements, while Amazon already emails recall alerts and free sites answer the warranty question.
