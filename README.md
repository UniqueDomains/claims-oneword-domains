# Available .CLAIMS One-Word Domains (20,523)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C523%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .claims one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,523 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,523 domains · **Median ask:** $19.81 · **High-demand under $2,500:** 3

**Last updated:** 2026-09-05
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

- `claims.csv`, public CSV extract (1,000 rows)
- `claims.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/claims-oneword-domains/main/claims.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                   |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| add.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |
| bond.claims   | resell    | —         | —             | high           | low    | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| dot.claims    | premium   | $500      | —             | high           | medium | 3      | name.com                                    |
| are.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |
| safe.claims   | resell    | —         | —             | high           | medium | 4      | NameCheap, Inc.                             |
| sex.claims    | premium   | $500      | —             | high           | medium | 3      | name.com                                    |
| ask.claims    | available | $19.99    | —             | high           | medium | 3      | name.com                                    |
| write.claims  | resell    | —         | —             | high           | low    | 5      | GoDaddy.com, LLC                            |
| Iam.claims    | premium   | $854      | $854          | high           | medium | 4      | namesilo                                    |
| bar.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |
| ohio.claims   | premium   | $500      | —             | high           | low    | 4      | name.com                                    |
| bid.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |
| first.claims  | premium   | $1,000    | $1,000        | high           | medium | 5      | name.com                                    |
| con.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |
| motor.claims  | premium   | $1,040    | $1,040        | high           | low    | 5      | namecheap                                   |
| dew.claims    | available | $19.99    | —             | medium         | low    | 3      | name.com                                    |
| berlin.claims | premium   | $500      | —             | high           | low    | 6      | name.com                                    |
| did.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |
| sports.claims | premium   | $128.70   | $128.70       | high           | medium | 6      | namecheap                                   |
| far.claims    | available | $19.99    | —             | high           | low    | 3      | name.com                                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,523 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/claims?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/claims?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=related_pricing)

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

This list covers single-word domain names on the .claims TLD, spanning everyday nouns and compound words like homes.claims, pictures.claims, and restassured.claims. With 12,442 names and a median asking price near $27, the selection suits insurance, legal, and warranty-related brands looking for a clear, category-specific web address. Updated daily, it reflects current asking prices across the full range of one-word .claims options.

- 12,442 single-word .claims domains available for evaluation
- Median asking price near $27 across this selection
- Compound one-word names like homes.claims, pictures.claims
- Well-suited for insurance, warranty, and legal claims brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CLAIMS One-Word Domains*. Version 2026-09-05. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CLAIMS page](https://unique.domains/domains/tld/claims?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
