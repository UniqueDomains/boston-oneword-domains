# Available .BOSTON One-Word Domains (13,422)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C422%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .boston one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,422 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,422 domains · **Median ask:** $39.51 · **High-demand under $2,500:** 11

**Last updated:** 2026-08-11
**Canonical page:** `https://unique.domains/domains/tld/boston`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/boston?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./boston.csv">CSV</a> / <a href="./boston.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BOSTON search](https://unique.domains/domains/tld/boston?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BOSTON search](https://unique.domains/domains/tld/boston?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BOSTON one-word domain catalog.

### Files

- `boston.csv`, public CSV extract (1,000 rows)
- `boston.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/boston-oneword-domains/main/boston.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| aery.boston    | available | $23.49    | $23.49        | low            | low    | 4      | namesilo                                                  |
| come.boston    | resell    | —         | —             | high           | low    | 4      | NameCheap, Inc.                                           |
| abo.boston     | premium   | $47.20    | $21.24        | low            | low    | 3      | namesilo                                                  |
| airy.boston    | available | $23.49    | $23.49        | low            | low    | 4      | namesilo                                                  |
| family.boston  | resell    | —         | —             | high           | medium | 6      | Global Domains International, Inc. DBA DomainCostClub.com |
| ape.boston     | premium   | $96       | $21.24        | medium         | low    | 3      | namesilo                                                  |
| arid.boston    | available | $24.98    | $30.98        | low            | low    | 4      | namecheap                                                 |
| salary.boston  | resell    | —         | —             | high           | low    | 6      | GoDaddy.com, LLC                                          |
| azo.boston     | premium   | $47.20    | $21.24        | low            | low    | 3      | namesilo                                                  |
| ashy.boston    | available | $23.49    | $23.49        | low            | low    | 4      | namesilo                                                  |
| airport.boston | resell    | —         | —             | medium         | low    | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| bag.boston     | premium   | $47.20    | $21.24        | high           | low    | 3      | namesilo                                                  |
| avid.boston    | available | $23.49    | $23.49        | medium         | low    | 4      | namesilo                                                  |
| success.boston | resell    | —         | —             | high           | low    | 7      | GoDaddy.com, LLC                                          |
| bus.boston     | premium   | $242      | $21.24        | high           | low    | 3      | namesilo                                                  |
| awed.boston    | available | $23.49    | $23.49        | low            | low    | 4      | namesilo                                                  |
| but.boston     | premium   | $47.20    | $21.24        | high           | low    | 3      | namesilo                                                  |
| back.boston    | available | $23.49    | $23.49        | high           | low    | 4      | namesilo                                                  |
| cry.boston     | premium   | $50       | —             | high           | low    | 3      | name.com                                                  |
| bass.boston    | available | $23.49    | $23.49        | medium         | low    | 4      | namesilo                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,422 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 11 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/boston?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/boston?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of one-word .boston domains spans 12,469 names, most priced under $500 with a median ask of $41.70. The set skews toward available inventory (11,286 names), with a smaller premium tier (1,116) and a thin resell layer (67). A handful of names, like show.boston and watch.boston, list well below reference value — useful signals whether you're comparing spread or shortlisting a brand.

- 12,469 one-word .boston domains, updated daily
- Median ask $41.70 — most listed under $500
- 11,286 available, 1,116 premium, 67 resell
- Undervalued picks like show.boston and watch.boston

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOSTON One-Word Domains*. Version 2026-08-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOSTON page](https://unique.domains/domains/tld/boston?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
