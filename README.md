# Available .BOSTON One-Word Domains (12,467)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C467%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .boston one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,467 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,467 domains · **Median ask:** $42.15 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `boston.csv` — public CSV extract (1,000 rows)
- `boston.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/boston-oneword-domains/main/boston.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| finals.boston   | available | $23.49    | $23.49        | 80             | 7      | 6      | namesilo         |
| jewels.boston   | available | $30.98    | —             | 80             | 15     | 6      | namecheap        |
| geton.boston    | available | $30.98    | —             | 82             | 10     | 6      | namecheap        |
| matcha.boston   | available | $30.98    | —             | 86             | 39     | 6      | namecheap        |
| Apples.boston   | available | $30.98    | —             | 90             | 16     | 6      | namecheap        |
| playin.boston   | available | $30.98    | —             | 80             | 10     | 7      | namecheap        |
| pierogi.boston  | available | $30.98    | —             | 82             | 7      | 7      | namecheap        |
| messages.boston | available | $23.49    | $23.49        | 80             | 16     | 8      | namesilo         |
| coins.boston    | available | $30.98    | —             | 56             | 41     | 5      | namecheap        |
| pops.boston     | resell    | —         | —             | 74             | 24     | 4      | GoDaddy.com, LLC |
| online.boston   | premium   | $250      | —             | 70             | 62     | 7      | name.com         |
| farmers.boston  | premium   | $100      | —             | 54             | 59     | 7      | name.com         |
| aliens.boston   | available | $23.49    | $23.49        | 56             | 35     | 6      | namesilo         |
| Tools.boston    | premium   | $56       | $25.20        | 56             | 40     | 5      | namecheap        |
| SanDiego.boston | available | $23.49    | $23.49        | 74             | 29     | 9      | namesilo         |
| teams.boston    | premium   | $50       | —             | 62             | 32     | 5      | name.com         |
| heroes.boston   | available | $30.98    | —             | 68             | 29     | 6      | namecheap        |
| partners.boston | premium   | $100      | —             | 61             | 32     | 8      | name.com         |
| backyard.boston | available | $30.98    | —             | 80             | 27     | 9      | namecheap        |
| William.boston  | premium   | $56       | $25.20        | 74             | 31     | 7      | namecheap        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,467 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/boston?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/boston?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=related_pricing)

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

These domains are all one-word names on the .boston extension. That makes the selection highly specific: the upside is clear geographic signaling, while the tradeoff is a narrower buyer and customer audience than mainstream extensions. Sample names like popup.boston, getup.boston, jewels.boston, and finals.boston show the mix of action words, commercial terms, and broad brandables in this set. For founders, the key question is whether a Boston-first identity helps the brand. For investors, the key question is whether the ask leaves enough room for resale despite the extension’s more limited liquidity. Median ask across the selection is 42.15.

- All names in this set use the .boston extension
- One-word format supports cleaner recall and branding
- Median ask is 42.15 across 12,467 domains
- Best fit when Boston relevance is part of the thesis

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOSTON One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOSTON page](https://unique.domains/domains/tld/boston?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_boston_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
