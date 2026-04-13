# Available .CLAIMS One-Word Domains (9,469)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C469%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C469%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .claims one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 9,469 rows · **Live catalog:** 9,469 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/claims`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/claims?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./claims.csv">CSV</a> / <a href="./claims.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CLAIMS search](https://unique.domains/domains/tld/claims?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CLAIMS search](https://unique.domains/domains/tld/claims?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CLAIMS one-word domain catalog.

### Files

- `claims.csv` — public CSV extract (9,469 rows)
- `claims.json` — public JSON extract (9,469 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/claims-oneword-domains/main/claims.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar      |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------- |
| silver.claims   | available | $82.98    | —             | 56             | 99     | 6      | namecheap      |
| get.claims      | resell    | —         | —             | 88             | 69     | 3      | Dynadot Inc    |
| business.claims | premium   | $1,040    | $1,040        | 100            | 53     | 8      | namecheap      |
| good.claims     | available | $19.99    | $86.99        | 82             | 55     | 4      | name.com       |
| mail.claims     | resell    | —         | —             | 94             | 59     | 4      | Sav.com, LLC   |
| one.claims      | premium   | $123.75   | $123.75       | 132            | 50     | 3      | name.com       |
| game.claims     | available | $19.99    | $86.99        | 120            | 50     | 4      | name.com       |
| live.claims     | resell    | —         | —             | 108            | 56     | 4      | Dynadot Inc    |
| travel.claims   | premium   | $1,040    | $1,040        | 115            | 48     | 6      | namecheap      |
| design.claims   | available | $19.99    | $86.99        | 108            | 50     | 6      | name.com       |
| smart.claims    | resell    | —         | —             | 74             | 56     | 5      | Sav.com, LLC   |
| all.claims      | premium   | $500      | $500          | 88             | 48     | 3      | name.com       |
| snap.claims     | available | $19.99    | $86.99        | 90             | 46     | 4      | name.com       |
| shop.claims     | resell    | —         | —             | 78             | 54     | 4      | Sav.com, LLC   |
| gold.claims     | premium   | $520      | $520          | 72             | 48     | 4      | namecheap      |
| genius.claims   | available | $19.99    | $86.99        | 98             | 45     | 6      | name.com       |
| best.claims     | resell    | —         | —             | 82             | 52     | 4      | Dynadot Inc    |
| trade.claims    | premium   | $128.70   | $128.70       | 116            | 46     | 5      | namecheap      |
| creative.claims | available | $19.99    | $86.99        | 92             | 45     | 8      | name.com       |
| world.claims    | resell    | —         | —             | 88             | 51     | 5      | InterNetX GmbH |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,469-row public sample | 9,469 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/claims?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/claims?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=related_pricing)

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
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CLAIMS One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CLAIMS page](https://unique.domains/domains/tld/claims?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
