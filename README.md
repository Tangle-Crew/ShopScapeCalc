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

Shop prices move by a fixed percentage with every item bought or sold, then reset back to the starting price on a world hop. ShopScape Calc models that curve and works out the batch size that gets closest to the ideal price for the fewest hops.

### 🔄 Sell or Buy

Toggle between selling (price drops per item) and buying (price rises per item).

### 🎯 Amount or Gold total

Solve for the profit or cost of a fixed item count, or for how many items it takes to hit a gold target.

### 📈 Suggested sweet spot

Automatically picks the batch size at the point of sharpest diminishing returns, plotted on an interactive chart alongside a full batch-size breakdown table.

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
