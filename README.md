# Available .CLAIMS One-Word Domains (12,438)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C438%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .claims one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,438 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,438 domains · **Median ask:** $31.19 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `claims.csv` — public CSV extract (1,000 rows)
- `claims.json` — public JSON extract (1,000 rows)
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

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Acup.claims         | available | $82.98    | —             | 80             | 5      | 5      | namecheap |
| WiFi.claims         | available | $82.98    | —             | 83             | 37     | 5      | namecheap |
| barup.claims        | available | $19.99    | —             | 82             | 2      | 6      | name.com  |
| Apples.claims       | available | $82.98    | —             | 90             | 16     | 6      | namecheap |
| playin.claims       | available | $19.99    | —             | 80             | 10     | 7      | name.com  |
| dogsick.claims      | available | $19.99    | —             | 90             | 1      | 7      | name.com  |
| getlife.claims      | available | $19.99    | —             | 80             | 5      | 8      | name.com  |
| online.claims       | premium   | $123.75   | —             | 70             | 62     | 7      | name.com  |
| neuroscience.claims | available | $19.99    | —             | 80             | 37     | 12     | name.com  |
| homes.claims        | premium   | $500      | —             | 86             | 34     | 5      | name.com  |
| spectra.claims      | available | $19.99    | —             | 62             | 34     | 7      | name.com  |
| SanDiego.claims     | premium   | $500      | —             | 74             | 29     | 9      | name.com  |
| etc.claims          | available | $19.99    | —             | 58             | 34     | 3      | name.com  |
| veterans.claims     | premium   | $500      | —             | 56             | 23     | 8      | name.com  |
| partners.claims     | available | $19.99    | —             | 61             | 32     | 8      | name.com  |
| maps.claims         | available | $19.99    | —             | 56             | 31     | 4      | name.com  |
| quotes.claims       | available | $19.99    | —             | 58             | 29     | 6      | name.com  |
| photos.claims       | available | $19.99    | —             | 54             | 28     | 6      | name.com  |
| pages.claims        | available | $19.99    | —             | 52             | 28     | 5      | name.com  |
| backyard.claims     | available | $19.99    | —             | 80             | 27     | 9      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,438 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is defined by one constraint: the domain ends in .claims. That creates a very specific naming set. Some entries read as direct claim-related keywords, while others are generic words adapted to the extension, such as Acup.claims, WiFi.claims, finals.claims, and forces.claims. For founders, the key question is whether the full domain reads clearly and feels ownable in context. For investors, the main check is whether the word and extension pair support realistic buyer intent at the current ask. With a median ask of 31.19, pricing may be approachable, but the extension itself still needs to carry the commercial meaning.

- Check whether the word reads naturally with .claims
- Favor clear, memorable words over awkward pairings
- Use the 31.19 median ask as a basic pricing anchor
- Be stricter on renewal risk with niche extensions

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CLAIMS One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CLAIMS page](https://unique.domains/domains/tld/claims?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_claims_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
