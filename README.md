# Available .LUXE One-Word Domains (18,246)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C246%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .luxe one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,246 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,246 domains · **Median ask:** $114.96 · **High-demand under $2,500:** 12

**Last updated:** 2026-08-21
**Canonical page:** `https://unique.domains/domains/tld/luxe`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/luxe?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./luxe.csv">CSV</a> / <a href="./luxe.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LUXE search](https://unique.domains/domains/tld/luxe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LUXE search](https://unique.domains/domains/tld/luxe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LUXE one-word domain catalog.

### Files

- `luxe.csv`, public CSV extract (1,000 rows)
- `luxe.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/luxe-oneword-domains/main/luxe.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| xci.luxe  | available | $27.99    | $27.99        | low            | low    | 3      | name.com         |
| aids.luxe | resell    | —         | —             | medium         | low    | 4      | GoDaddy.com, LLC |
| aaa.luxe  | premium   | $242      | $17.70        | high           | medium | 3      | namesilo         |
| ague.luxe | available | $27.99    | $27.99        | low            | low    | 4      | name.com         |
| book.luxe | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| any.luxe  | premium   | $250      | —             | high           | medium | 3      | name.com         |
| alky.luxe | available | $19.49    | $19.49        | low            | low    | 4      | namesilo         |
| cook.luxe | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC |
| arc.luxe  | premium   | $242      | $17.70        | medium         | medium | 3      | namesilo         |
| auld.luxe | available | $19.49    | $19.49        | low            | low    | 4      | namesilo         |
| just.luxe | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| bae.luxe  | premium   | $242      | $17.70        | high           | low    | 3      | namesilo         |
| avon.luxe | available | $19.49    | $19.49        | high           | low    | 4      | namesilo         |
| love.luxe | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| bow.luxe  | premium   | $242      | $17.70        | high           | low    | 3      | namesilo         |
| beam.luxe | available | $19.49    | $19.49        | medium         | medium | 4      | namesilo         |
| play.luxe | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| clx.luxe  | premium   | $242      | $17.70        | low            | low    | 3      | namesilo         |
| bump.luxe | available | $19.49    | $19.49        | medium         | low    | 4      | namesilo         |
| snow.luxe | resell    | —         | —             | medium         | low    | 4      | GoDaddy.com, LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 18,246 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 12 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/luxe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/luxe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=related_pricing)

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

This list of one-word .luxe domain names spans 12,703 entries, from freshly available names like beawake.luxe and chaitea.luxe to premium and resale listings such as Snickers.luxe and NewYork.luxe. Most names cluster under $500, with a smaller premium tier reaching into the thousands. Modern-sounding names dominate, followed by elegant and playful tones, giving both investors and founders a wide, low-cost pool to compare before committing to a specific name.

- 10,938 available, 1,480 premium, 285 resale .luxe names
- 81% priced under $500; median ask near $153
- Modern tone leads; elegant and playful themes follow
- 29 names rank in the top 15% for demand

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LUXE One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LUXE page](https://unique.domains/domains/tld/luxe?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
