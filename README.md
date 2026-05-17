# Available .FUN One-Word Domains (10,465)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C465%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fun one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,465 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,465 domains · **Median ask:** $140.83 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
**Canonical page:** `https://unique.domains/domains/tld/fun`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fun?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fun.csv">CSV</a> / <a href="./fun.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FUN search](https://unique.domains/domains/tld/fun?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FUN search](https://unique.domains/domains/tld/fun?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FUN one-word domain catalog.

### Files

- `fun.csv` — public CSV extract (1,000 rows)
- `fun.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fun-oneword-domains/main/fun.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| dogsit.fun      | available | $4.99     | —             | 96             | 2      | 6      | name.com                                            |
| toneup.fun      | available | $4.99     | —             | 80             | 5      | 7      | name.com                                            |
| leaveon.fun     | available | $4.99     | —             | 80             | 1      | 8      | name.com                                            |
| fitinto.fun     | available | $4.99     | —             | 84             | 1      | 8      | name.com                                            |
| chaitea.fun     | available | $4.99     | —             | 86             | 3      | 8      | name.com                                            |
| dogstail.fun    | available | $4.99     | —             | 94             | 1      | 8      | name.com                                            |
| becalled.fun    | available | $2.99     | $41.99        | 86             | 2      | 9      | namesilo                                            |
| turninto.fun    | available | $4.99     | —             | 86             | 3      | 9      | name.com                                            |
| cuddleup.fun    | available | $4.99     | —             | 89             | 4      | 9      | name.com                                            |
| fasttimes.fun   | available | $4.99     | —             | 80             | 3      | 10     | name.com                                            |
| herbaltea.fun   | available | $4.99     | —             | 80             | 5      | 10     | name.com                                            |
| RedSox.fun      | available | $33.48    | —             | 72             | 60     | 7      | namecheap                                           |
| ingredients.fun | resell    | $4.99     | —             | 56             | 14     | 11     | Chengdu West Dimension Digital Technology Co., Ltd. |
| winners.fun     | premium   | $156.25   | —             | 60             | 81     | 7      | name.com                                            |
| jetlag.fun      | available | $4.99     | —             | 72             | 17     | 7      | name.com                                            |
| movies.fun      | resell    | —         | —             | 80             | 28     | 6      | Namify Domains Inc                                  |
| Books.fun       | premium   | $1,750    | $7,000        | 52             | 49     | 5      | namecheap                                           |
| moveit.fun      | available | $4.99     | —             | 77             | 13     | 7      | name.com                                            |
| consensus.fun   | resell    | —         | —             | 78             | 26     | 9      | Spaceship, Inc.                                     |
| jobs.fun        | premium   | $1,562.50 | —             | 79             | 42     | 4      | name.com                                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,465 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fun?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fun?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of .fun domains. The extension signals informality, entertainment, light consumer use, and playful branding rather than default corporate trust. Names such as Acup.fun, toneup.fun, hangon.fun, and QandA.fun show a mix of short phrases, action words, and conversational constructions. For founders, the main question is whether the name is memorable, easy to say, and still credible with a .fun ending. For investors, the key issue is selectivity: .fun can be inexpensive to enter, but buyer depth is narrower than for mainstream extensions. When comparing these domains, focus on clarity, commercial use case, and whether the keyword fits a fun-first brand position.

- All results use the .fun extension
- Median ask across this set is $140.83
- Best fit for playful, casual, consumer-facing brands
- Prioritize clear words and natural phrase flow

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FUN One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FUN page](https://unique.domains/domains/tld/fun?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fun_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
