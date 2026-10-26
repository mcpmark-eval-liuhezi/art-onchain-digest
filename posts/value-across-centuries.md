# Value Across Centuries: Rembrandt and LINK

*The Sunday Digest — this week's theme: value across four centuries.*

Every Sunday we put two things side by side that shouldn't have anything to do with each other. This week: the most famous painting in the Rijksmuseum, and a live price feed on Ethereum. One is 384 years old; the other is seconds old when you read it. Both, in their own way, are instruments for asking what something is worth — and who gets to decide.

---

## The Market Corner: Chainlink (LINK)

**Price: $11.47 USD** (as of 2026-10-26T08:52:31.423Z — the timestamp is taken directly from the price feed's own `lastUpdatedAt` field, so you know exactly how fresh this is by the time you read it).

- **Token:** Chainlink (LINK)
- **Contract:** `0x514910771AF9Ca656af840dff83E8264EcF986CA` (Ethereum mainnet)
- **Source:** live onchain price lookup by contract address on eth-mainnet, with the feed's update timestamp attached

LINK is the settlement layer's connective tissue: oracles that carry off-chain data into smart contracts. The price above isn't a screenshot from a dashboard — it's pulled straight from the token's mainnet contract, with the feed's own update timestamp attached. Value, verified at the moment of capture. Remember that phrase. It comes back later.

## The Art Corner: The Night Watch

**Object number SK-C-5, Rijksmuseum — painted in 1642.**

The museum catalogs Rembrandt's masterpiece — formally *Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'* — under object number **SK-C-5**, and dates it to **1642**. Both details come straight from the museum's own collection record, which is exactly the standard we hold this digest to.

Key facts from the record:

- **Year: 1642** — the confirmed date on the museum's official record for SK-C-5.
- **It's a militia company portrait, not a night scene.** The full catalog title names the subjects: Captain Frans Banninck Cocq's civic guard company and Lieutenant Willem van Ruytenburch. The "night" is an accident of darkened varnish, not of design.
- **Oil on canvas.** The museum's collection search returns this painting under the material "oil paint" (olieverf), and its machine-readable record carries a structured materials field (`made_of`) for the work — confirming it's catalogued as oil paint rather than tempera or a panel. The record also carries a structured dimensions field (`dimension`) for the painting.
- **Pulled from the museum's machine-readable record, not a screenshot.** The record resolves to object number SK-C-5 (record id https://id.rijksmuseum.nl/200107928), confirms the 1642 date, and carries structured materials and dimensions fields. For the exact centimeter figures, we defer to the museum's own collection page for SK-C-5 — that's the authoritative source, and we'd rather send you there than paraphrase it.

## A Career, in Dated Works

To show how one painter's value compounded over a lifetime, here is a short chronology of Rembrandt's career drawn from the Rijksmuseum's own collection data — dated works spanning nearly forty years:

| Year | Work | Object Number |
|------|------|---------------|
| 1626 | *Allegorisch musicerend gezelschap* | SK-A-4674 |
| 1628 | *Self-Portrait at an Early Age* | SK-A-4691 |
| 1634 | *Portrait of Haesje Jacobsdr van Cleyburg* | SK-A-4833 |
| 1635 | *An oriental* | SK-A-3340 |
| 1638 | *De stenen brug* | SK-A-1935 |
| 1639 | *Portrait of a woman, probably Maria Trip* | SK-C-597 |
| **1642** | ***The Night Watch*** | **SK-C-5** |
| 1660 | *De verloochening van Petrus* | SK-A-3137 |
| 1660 | *Rembrandt's son in a monk's habit, possibly as St Francis of Assisi* | SK-A-3138 |
| 1662 | *De Staalmeesters: the Amsterdam lakenbekers' guild college of weights and measures* | SK-C-6 |
| 1665 | *The Jewish Bride* | SK-C-216 |

Read down that column of years. In 1626 Rembrandt is painting allegorical music scenes. In 1642 he paints the Night Watch. In 1660 — nearly twenty years on, and after selling off his own collections to pay his creditors — he paints *The Syndics*, and in 1665 *The Jewish Bride*. The market priced him at rock bottom in his final decade. The record, four centuries later, disagrees. That's the long end of the compounding curve.

## The Comparison

Here is the whole thought in two lines:

| | **The Night Watch (SK-C-5)** | **Chainlink (LINK)** |
|---|---|---|
| Value today | Enshrined, the anchor of the Rijksmuseum's Gallery of Honour | $11.47 USD |
| Last updated | 1642 (record confirmed) | 2026-10-26T08:52:31.423Z |
| Settlement | Canonical, dispute-free | Onchain, oracle-fed |
| Age of the asset | 384 years | Minutes since last price update |
| Who decides worth | Four centuries of viewers | Everyone trading right now |

One asset refreshes every few seconds and can be re-verified by anyone with a node. The other refreshed once, in 1642, and has been settling ever since. The Night Watch has an update timestamp too — it's just that Rembrandt's was published 384 years ago and nobody has overwritten it since.

That's the trade: LINK gives you **value, verified at the moment of capture**. Rembrandt gives you value verified over four centuries. Both markets are open around the clock; only one of them has been open for 384 years.

---

*Sources: Rijksmuseum collection records (SK-C-5 and related object records, retrieved via the museum's data services; record id https://id.rijksmuseum.nl/200107928); onchain price data for LINK on Ethereum mainnet at contract `0x514910771AF9Ca656af840dff83E8264EcF986CA`, price timestamp 2026-10-26T08:52:31.423Z (lastUpdatedAt).*

*Prices move. The painting doesn't. See you next Sunday.*