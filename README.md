# ShopScape Calc

A shop-price calculator for **Tangle Crew** in [Old School RuneScape](https://oldschool.runescape.com/).

> **Built with the assistance of Claude by Anthropic — an AI coding assistant.**

## Tangle Crew

**Discord:** https://discord.gg/tanglecrew

**Wise Old Man:** wiseoldman.net/groups/12447

**OSRS Clan Finder:** https://osrsclanfinder.com/clans/tangle-crew

**OSRS Clans:** https://osrsclans.cc/clans/tanglecrew

---

## What it does

ShopScape Calc is two calculators in one page, switched with a tab at the top.

### General Calc

Shop prices move by a fixed percentage with every item bought or sold, then reset back to the starting price on a world hop. General Calc models that curve and works out the batch size that gets closest to the ideal price for the fewest hops.

- **🔄 Sell or Buy** — toggle between selling (price drops per item) and buying (price rises per item).
- **🎯 Amount or Gold total** — solve for the profit or cost of a fixed item count, or for how many items it takes to hit a gold target.
- **📦 Max stock (optional)** — cap the batch size at however much a shop actually holds, when that's smaller than your item count or step would otherwise sweep to.
- **📈 Suggested sweet spot** — automatically picks the batch size at the point of sharpest diminishing returns, plotted on an interactive chart alongside a full batch-size breakdown table.

### Onyx Calc

Sell Chaos and Death runes to [TzHaar-Mej-Roh's Rune Store](https://oldschool.runescape.wiki/w/TzHaar-Mej-Roh%27s_Rune_Store) for Tokkul, then see how many uncut onyx that buys from [TzHaar-Hur-Lek's Ore and Gem Store](https://oldschool.runescape.wiki/w/TzHaar-Hur-Lek%27s_Ore_and_Gem_Store) — themed after Mor Ul Rek, using the shops' real (linear, floor-capped) pricing instead of the General Calc's world-hop model.

- **🧤 Karamja gloves** — toggle the better rune sell-back rate and onyx price the gloves (tier 1+) give you.
- **💰 Starting Tokkul** — add Tokkul you already have on top of whatever the runes earn.
- **🔶 Uncut onyx affordable** — shown to the nearest tenth rather than floored, so you can see how close you are.

---

## Usage

Live at **[shopscapecalc.tanglecrew.group](https://shopscapecalc.tanglecrew.group)**.

It's a single static `index.html` — no build step, no backend, no dependencies. Everything runs client-side, so you can also just download the file and open it directly in a browser.

---

## Built With

- Vanilla HTML/CSS/JS
- Inline SVG — chart rendering
- GitHub Pages — hosting
- Claude by Anthropic — development assistance

---

## License

[MIT](LICENSE)
