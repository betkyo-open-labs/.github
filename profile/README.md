# Betkyo

![How the Journal verifies a number](cover.webp)

Betkyo is a crypto casino built in Tokyo around provably fair original games. This organisation publishes the parts of that claim you can check yourself:

- **[provably-fair-verifier](https://github.com/betkyo-open-labs/provably-fair-verifier)** — recompute any round from the revealed server seed, your client seed, the nonce and the cursor, with the same byte-to-number construction the site's browser verifier uses.
- **[odds-data](https://github.com/betkyo-open-labs/odds-data)** — the paytables and outcome distributions behind the Journal's figures, exported from engine source as JSON and CSV (CC BY 4.0). Canonical copies at [betkyo.com/data](https://betkyo.com/data/index.json).
- **[odds-derivations](https://github.com/betkyo-open-labs/odds-derivations)** — the scripts that turn those tables into the returns the articles quote: keno, Plinko, blackjack dealer outcomes, bingo.

The rule behind all of it: a game figure is printed only after it has been read from the code that pays it. [How the Journal verifies a number](https://betkyo.com/en/blog/how-the-journal-verifies-a-number-methodology/) · [The Journal](https://betkyo.com/en/blog/)

18+. Provably fair means the randomness is committed and checkable; every game still has a published house edge.
