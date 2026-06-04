# Available .AUCTION One-Word Domains (12,443)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C443%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .auction one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,443 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,443 domains · **Median ask:** $35.61 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
**Canonical page:** `https://unique.domains/domains/tld/auction`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/auction?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./auction.csv">CSV</a> / <a href="./auction.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .AUCTION search](https://unique.domains/domains/tld/auction?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .AUCTION search](https://unique.domains/domains/tld/auction?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .AUCTION one-word domain catalog.

### Files

- `auction.csv` — public CSV extract (1,000 rows)
- `auction.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/auction-oneword-domains/main/auction.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| fallen.auction      | available | $4.99     | —             | 82             | 11     | 6      | name.com  |
| crowd.auction       | available | $4.99     | —             | 98             | 33     | 5      | name.com  |
| inspiring.auction   | available | $4.99     | —             | 92             | 13     | 9      | name.com  |
| cherryontop.auction | available | $4.99     | —             | 82             | 9      | 13     | name.com  |
| pull.auction        | available | $4.99     | —             | 104            | 21     | 4      | name.com  |
| component.auction   | available | $4.99     | $52.99        | 84             | 19     | 9      | name.com  |
| bravery.auction     | available | $4.99     | —             | 80             | 12     | 7      | name.com  |
| chief.auction       | available | $4.99     | —             | 120            | 30     | 5      | name.com  |
| rooms.auction       | premium   | $242      | $242          | 80             | 27     | 5      | namesilo  |
| resounding.auction  | available | $4.99     | —             | 88             | 5      | 10     | name.com  |
| midFebruary.auction | available | $4.99     | —             | 98             | 1      | 12     | name.com  |
| concoct.auction     | available | $4.99     | —             | 109            | 4      | 7      | name.com  |
| squirrel.auction    | available | $4.99     | —             | 88             | 27     | 8      | name.com  |
| different.auction   | available | $4.99     | $52.99        | 100            | 25     | 9      | name.com  |
| bead.auction        | available | $4.99     | —             | 92             | 15     | 4      | name.com  |
| glitter.auction     | available | $4.99     | —             | 96             | 18     | 7      | name.com  |
| tech.auction        | premium   | $500      | —             | 104            | 48     | 4      | name.com  |
| atheist.auction     | available | $4.99     | —             | 88             | 11     | 7      | name.com  |
| silent.auction      | premium   | —         | —             | 80             | 24     | 6      | —         |
| piss.auction        | available | $4.99     | —             | 112            | 26     | 4      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,443 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/auction?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/auction?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is entirely made up of .auction domains, which makes extension fit the first test. The strongest names read naturally with .auction and describe a category, audience, or brand position without needing explanation. Examples such as crowd.auction, rooms.auction, and fallen.auction show the range: some are direct commercial keywords, while others are more abstract and depend on branding strength. With a median ask of 42.64, price may be accessible, but selection still matters. When comparing these domains, weigh how clearly the keyword matches auction use, how easy the name is to say and remember, and whether the full domain looks credible enough for resale or launch.

- Prioritize names that read naturally with .auction
- Direct keywords often beat abstract terms for clarity
- Check renewal fit before judging a low ask as a deal
- Avoid names that feel awkward when spoken aloud

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .AUCTION One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .AUCTION page](https://unique.domains/domains/tld/auction?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_auction_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
