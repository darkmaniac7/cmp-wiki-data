# cmp.wiki data

Daily JSON snapshots of the structured tables on [cmp.wiki](https://cmp.wiki/), the community reference for the NVIDIA CMP 170HX (8 GB and 10 GB cards).

| File | What |
|---|---|
| `Recipe.json` | Models running on CMP 170HX cards: engine, quant, card count, decode and prefill tok/s, link, P2P, power, status, tester |
| `Platform.json` | Boards and servers with the settings that mattered |
| `Confirmation.json` | Second-person reproductions of recipes, platforms and unlocks |
| `Unlocks.json` | What each unlock build opens, per driver version and card variant |
| `SellerReport.json` | Sourced buyer reports about named sellers (see the wiki's Seller history page for the rules) |
| `index.json` | Field names and row counts |

Each row carries the Discord handle that reported it. Status words (Proven, Reported, Theory, Contested, Warning) are explained on [Status taxonomy](https://cmp.wiki/wiki/Status_taxonomy). Live queries and the full API are described on [For agents](https://cmp.wiki/wiki/CMP_Wiki:For_agents).

License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Credit cmp.wiki and the handle on each row.
