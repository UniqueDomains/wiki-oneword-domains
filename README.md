# Available .WIKI One-Word Domains (10,768)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C768%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .wiki one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,768 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,768 domains · **Median ask:** $23.69 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/wiki`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/wiki?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./wiki.csv">CSV</a> / <a href="./wiki.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WIKI search](https://unique.domains/domains/tld/wiki?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WIKI search](https://unique.domains/domains/tld/wiki?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WIKI one-word domain catalog.

### Files

- `wiki.csv` — public CSV extract (1,000 rows)
- `wiki.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/wiki-oneword-domains/main/wiki.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| RedSox.wiki      | available | $43.98    | —             | 72             | 60     | 7      | namecheap                                    |
| insight.wiki     | resell    | —         | —             | 76             | 69     | 8      | Xiamen ChinaSource Internet Service Co., Ltd |
| Books.wiki       | premium   | $140      | $140          | 52             | 49     | 5      | namecheap                                    |
| backyard.wiki    | available | $2.99     | —             | 80             | 27     | 9      | name.com                                     |
| solutions.wiki   | resell    | —         | —             | 56             | 31     | 9      | DNSPod, Inc.                                 |
| jobs.wiki        | premium   | $312.50   | —             | 79             | 42     | 4      | name.com                                     |
| destination.wiki | available | $2.99     | —             | 90             | 25     | 11     | name.com                                     |
| schools.wiki     | resell    | —         | —             | 72             | 24     | 7      | Xiamen ChinaSource Internet Service Co., Ltd |
| maps.wiki        | premium   | $125      | —             | 56             | 31     | 4      | name.com                                     |
| flights.wiki     | available | $2.99     | —             | 61             | 22     | 7      | name.com                                     |
| boats.wiki       | resell    | —         | —             | 52             | 24     | 5      | Dynadot Inc                                  |
| heroes.wiki      | premium   | $125      | —             | 68             | 29     | 6      | name.com                                     |
| origins.wiki     | available | $2.99     | —             | 46             | 22     | 7      | name.com                                     |
| apartments.wiki  | resell    | —         | —             | 60             | 21     | 10     | GoDaddy.com, LLC                             |
| comics.wiki      | premium   | $125      | —             | 68             | 24     | 6      | name.com                                     |
| Alexis.wiki      | available | $2.99     | —             | 72             | 21     | 6      | name.com                                     |
| communities.wiki | resell    | —         | —             | 68             | 19     | 11     | Sav.com LLC                                  |
| weddings.wiki    | premium   | $116      | $116          | 64             | 18     | 8      | namesilo                                     |
| designs.wiki     | available | $2.99     | —             | 72             | 21     | 7      | name.com                                     |
| pestcontrol.wiki | resell    | —         | —             | 74             | 18     | 12     | GoDaddy.com, LLC                             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,768 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/wiki?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/wiki?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .wiki domains, so the extension itself shapes how each name will be read. Terms like office.wiki, devote.wiki, and pandabear.wiki are direct and easy to parse, but they work best when the word pairs naturally with a knowledge, reference, or community use case. For founders, the main question is whether the keyword is memorable enough to carry a non-mainstream extension. For investors, the key is buyability at the ask and whether the word has enough breadth to attract multiple end users. With a median ask of 23.69, pricing may be accessible, but extension fit still matters more than raw word quality.

- Prioritize words that naturally fit a reference or knowledge use
- Compare ask price against the strength of the keyword
- Generic terms can be clearer than playful terms on .wiki
- Check trademark risk on branded or highly specific words

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WIKI One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WIKI page](https://unique.domains/domains/tld/wiki?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wiki_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
