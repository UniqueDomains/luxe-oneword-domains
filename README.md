# Available .LUXE One-Word Domains (5,622,451)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C686%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C451%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .luxe one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,686-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,451 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/luxe`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/luxe?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_open_search"><b>Open live .LUXE search</b></a> ·
  <a href="https://unique.domains/domains/tld/luxe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_create_radar"><b>Create .LUXE Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/luxe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./luxe.csv"><b>Download CSV</b></a> ·
  <a href="./luxe.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LUXE one-word domain catalog.

### Files

- `luxe.csv` — public CSV extract (9,686 rows)
- `luxe.json` — public JSON extract (9,686 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

### Use this repo to

- inspect a public sample
- download CSV or JSON
- cite the dataset
- understand the fields and scoring inputs

### Use the live page to

- keep the exact search context
- search the full .LUXE catalog
- filter by price, demand, status, spelling risk, and fit
- save the exact search as a Radar
- turn the search into a founder Project

## 📊 Snapshot of the live .LUXE catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

**Why this chart:** it gives a fast overview of the live search composition using the same preview payload that supplies the README counts.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/luxe-oneword-domains/main/luxe.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | purchase_price | renewal_price | attractiveness | demand | length | registrar        |
| --------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ | ---------------- |
| seventeen.luxe  | available | $27.99         | $27.99        | 84             | 62     | 9      | name.com         |
| energy.luxe     | resell    | $37,060.64     | —             | 78             | 46     | 6      | Dynadot Inc      |
| nationwide.luxe | premium   | $2,500         | $27.99        | 76             | 66     | 10     | name.com         |
| fast.luxe       | available | $27.99         | $27.99        | 82             | 53     | 4      | name.com         |
| mint.luxe       | resell    | —              | —             | 72             | 78     | 4      | GoDaddy.com, LLC |
| live.luxe       | premium   | $1,000         | $27.99        | 108            | 55     | 4      | name.com         |
| forge.luxe      | available | $27.99         | $27.99        | 62             | 45     | 5      | name.com         |
| fire.luxe       | resell    | —              | —             | 70             | 75     | 4      | GoDaddy.com, LLC |
| zero.luxe       | premium   | $1,000         | $27.99        | 112            | 53     | 4      | name.com         |
| creator.luxe    | available | $27.99         | $27.99        | 70             | 44     | 7      | name.com         |
| boss.luxe       | resell    | —              | —             | 76             | 73     | 4      | GoDaddy.com, LLC |
| design.luxe     | premium   | $2,500         | $27.99        | 108            | 50     | 6      | name.com         |
| track.luxe      | available | $27.99         | $27.99        | 94             | 42     | 5      | name.com         |
| hello.luxe      | resell    | —              | —             | 130            | 71     | 5      | Spaceship, Inc.  |
| clear.luxe      | premium   | $100           | $27.99        | 90             | 50     | 5      | name.com         |
| quick.luxe      | available | $27.99         | $27.99        | 72             | 41     | 5      | name.com         |
| guess.luxe      | resell    | —              | —             | 78             | 71     | 5      | GoDaddy.com, LLC |
| travel.luxe     | premium   | $5,520         | $17.70        | 115            | 48     | 6      | namesilo         |
| gather.luxe     | available | $27.99         | $27.99        | 96             | 38     | 6      | name.com         |
| fuck.luxe       | resell    | —              | —             | 124            | 70     | 4      | GoDaddy.com, LLC |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LUXE One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LUXE page](https://unique.domains/domains/tld/luxe?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_luxe_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
