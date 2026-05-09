# Available .PW One-Word Domains (11,408)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C408%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .pw one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,408 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,408 domains · **Median ask:** $157.97 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/pw`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/pw?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./pw.csv">CSV</a> / <a href="./pw.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PW search](https://unique.domains/domains/tld/pw?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PW search](https://unique.domains/domains/tld/pw?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PW one-word domain catalog.

### Files

- `pw.csv` — public CSV extract (1,000 rows)
- `pw.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/pw-oneword-domains/main/pw.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| torch.pw    | premium   | —         | —             | 80             | 25     | 5      | —                                                       |
| barup.pw    | available | $20.48    | —             | 82             | 2      | 6      | namecheap                                               |
| geton.pw    | available | $20.48    | —             | 82             | 10     | 6      | namecheap                                               |
| playin.pw   | available | $20.48    | —             | 80             | 10     | 7      | namecheap                                               |
| QandA.pw    | available | $20.48    | —             | 80             | 10     | 7      | namecheap                                               |
| hangon.pw   | available | $20.48    | —             | 82             | 6      | 7      | namecheap                                               |
| pierogi.pw  | available | $20.48    | —             | 82             | 7      | 7      | namecheap                                               |
| dogsick.pw  | available | $20.48    | —             | 90             | 1      | 7      | namecheap                                               |
| rumcake.pw  | available | $20.48    | —             | 81             | 3      | 8      | namecheap                                               |
| FabFour.pw  | available | $3.99     | $24.49        | 82             | 3      | 8      | namesilo                                                |
| lightup.pw  | available | $20.48    | —             | 82             | 15     | 8      | namecheap                                               |
| surebet.pw  | available | $20.48    | —             | 82             | 8      | 8      | namecheap                                               |
| CocaCola.pw | available | $20.48    | —             | 92             | 82     | 9      | namecheap                                               |
| coins.pw    | resell    | —         | —             | 56             | 41     | 5      | GoDaddy.com, LLC                                        |
| online.pw   | premium   | $3,745.83 | —             | 70             | 62     | 7      | name.com                                                |
| RedSox.pw   | available | $20.48    | —             | 72             | 60     | 7      | namecheap                                               |
| Tools.pw    | resell    | —         | —             | 56             | 40     | 5      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| agents.pw   | premium   | $187.29   | —             | 56             | 50     | 6      | name.com                                                |
| stories.pw  | available | $20.48    | —             | 58             | 36     | 7      | namecheap                                               |
| webs.pw     | resell    | —         | —             | 56             | 21     | 4      | Chengdu West Dimension Digital Technology Co., Ltd.     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,408 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/pw?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/pw?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=related_pricing)

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

This selection is entirely focused on .pw domains. The mix includes short dictionary words, verbs, broad phrases, and niche terms such as torch.pw, finals.pw, geton.pw, dogsit.pw, and edamame.pw. For founders, the main question is whether a .pw ending still leaves the name memorable and credible enough for a real brand. For investors, the key issue is whether the word itself is strong enough to offset a less mainstream extension. With a median ask of 157.79, price discipline matters less than name quality, clarity, and any obvious trademark or category risk in the second-level term.

- Prioritize strong words that still read cleanly with .pw
- Check whether the term is generic or trademark-sensitive
- Compare broad-use words against narrow niche phrases
- Use the 157.79 median ask as a basic price anchor

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PW One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PW page](https://unique.domains/domains/tld/pw?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pw_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
