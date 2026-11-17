# Kazakhstan Marketing Kit

Four agent skills for marketing a business in Kazakhstan. Each one carries dated facts from official sources, reference files with the tables and wording behind them, and a short working method, so an assistant stops answering Kazakhstan questions with advice written for other markets.

| Skill | Use it for |
|---|---|
| `kz-marketplace-seller` | Selling on the Kaspi.kz marketplace: commission and delivery tariffs for 2026, margin per order, product card requirements, paid promotion, rating and reviews, quality indicators and what gets a shop switched off, what the rules forbid |
| `kz-maps-listing` | Company cards, reviews and paid placement on 2GIS, Google Maps and Yandex Maps: 2GIS review rules and the dispute procedure, how to report a review on Google and Yandex, what Yandex sells in Kazakhstan, break-even before buying a package |
| `kz-ad-compliance` | Checking an ad against Kazakhstan's advertising law: language, tenge, licences, banned categories, finance and microcredit, courses, blogger and sponsored posts with the official marking wordings, healthcare advertising, fines in MRP and in tenge for 2026 |
| `kz-digital-channels` | Search, social and messenger channels: Google and Yandex shares, platform reach, Telegram, paid search in tenge, Kazakh and Russian page versions, a channel plan |

The skills answer in the language the user writes in: Russian, Kazakh or English.

Not covered: other marketplaces, WhatsApp, product marking and conformity documents, personal-data and messaging consent, consumer returns.

## Install

Claude Code, from GitHub:

```
/plugin marketplace add 2gelbuy/kz-marketing-skills
/plugin install kz-marketing@konabayev
```

Claude Code, from a local copy of this folder:

```bash
claude --plugin-dir ./kz-marketing-skills
```

Any other agent that reads `SKILL.md` files: copy the folders under `skills/` into its skills directory.

## What the plugin runs

Nothing. It contains only Markdown: four skills and their reference files. It has no hooks, scripts, MCP servers or commands, sends no data anywhere and asks for no keys. The links inside the skills point to official pages the assistant may open or cite.

## What the facts rest on

Every market fact is listed in [SOURCES.md](SOURCES.md) with its URL and the date it was read. The same file lists what was not verified. Rules, commissions and audience figures change; the skills tell the assistant to send the user to the source before money or account risk is involved.

The skills are independent work. They are not affiliated with or endorsed by Kaspi.kz, 2GIS, Google, Yandex, Meta, TikTok or any government body. `kz-ad-compliance` is a first-pass check, not legal advice.

## Author

Tugelbay Konabayev, digital marketer in Almaty: <https://konabayev.com>. A short overview of the kit, in English and Russian: <https://konabayev.com/tools/kazakhstan-marketing-skills/>.

Corrections are welcome as GitHub issues: a rule that changed, a figure that moved, a wrong link.

Licence: MIT, see [LICENSE](LICENSE).
