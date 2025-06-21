```markdown
# PropChain Public Roadmap 📈

> **🚧 Internal-Use Only – Not Open Source**  
> The content of this repository is proprietary to **PropChain LLC**.  
> Redistribution, forking, copying, or public disclosure (in whole or part) is **strictly prohibited** without prior written consent.

---

## Table of Contents
1. [Purpose](#purpose)  
2. [Phase Glossary](#phase-glossary)  
3. [Repository Layout](#repository-layout)  
4. [Getting Started](#getting-started)  
5. [Docs & GitHub Pages](#docs--github-pages)  
6. [Contributing](#contributing)  
7. [License](#license)  

---

## Purpose
This repo tracks PropChain’s **high-level product roadmap** – milestones, themes, and outcomes – across six release phases.  
It contains **no application source code**; only planning artifacts and lightweight automation scripts so teams and stakeholders can stay aligned.

---

## Phase Glossary
| Phase | Public Name | Scope |
|-------|-------------|-------|
| **1** | Pre-Alpha (Foundational R&D) | Cloud & data foundations, initial AI/ML, compliance baseline |
| **2** | Alpha Launch (First External Exposure) | First mobile builds, real-time APIs, enhanced search & predictive UX |
| **3** | Beta Launch (Predictive Intelligence) | Scenario simulators, clustering, investor dashboards |
| **4** | Go-To-Market Launch | Consumer & pro apps live, blockchain workflows, GTM reporting |
| **5** | Post-GTM Expansion | Scaling infra, API monetization, nationwide data coverage |
| **6** | Continuous R&D & Expansion | International scale, advanced market tools, continuous AI evolution |

---

## Repository Layout

```markdown
propchain-public-roadmap/
├─ README.md
├─ ROADMAP_ISSUES.csv         # canonical roadmap list
├─ docs/                      # published via GitHub Pages
│  ├─ index.md                # landing page
│  ├─ phases/                 # one file per phase
│  │  ├─ phase-1-pre-alpha.md
│  │  ├─ phase-2-alpha.md
│  │  ├─ phase-3-beta.md
│  │  ├─ phase-4-go-to-market.md
│  │  ├─ phase-5-post-gtm.md
│  │  └─ phase-6-continuous-rnd.md
│  └─ assets/                 # images / diagrams
├─ scripts/
│  └─ import_issues_from_csv.py
└─ .github/
   ├─ ISSUE_TEMPLATE/
   │  └─ roadmap_item.yml
   └─ workflows/
      └─ deploy-docs.yml  
````
---

## Getting Started
1. **Clone**  
```bash
   git clone git@github.com:PropChain-App/propchain-public-roadmap.git
   cd propchain-public-roadmap
````

2. **Install helper deps** (optional)

   ```bash
   pip install -r scripts/requirements.txt   # requests, python-dotenv, etc.
   ```
3. **Add or edit roadmap rows** in `ROADMAP_ISSUES.csv`.

---

## Docs & GitHub Pages

The contents of **`docs/`** are automatically published at
`https://propchain-app.github.io/propchain-public-roadmap/` (private-link only).

* `index.md` – overview landing page
* `phases/phase-X-*.md` – deeper dive per release phase
* `assets/` – diagrams, screenshots, decks (linked in the docs)

To preview locally:

```bash
npx serve docs     # or use GitHub Desktop → "Open in Browser"
```

---

## Contributing

This repository is **read-only** for most team members.
If you need to revise the roadmap:

1. **Open an Issue** using the *Roadmap Item* template, or
2. **Submit a Pull Request** that updates the CSV / docs.

All changes require **approval from the PMO** before merge.

---

## License

**Proprietary — All Rights Reserved**
Copyright © PropChain LLC.
No license is granted to view, modify, or distribute outside PropChain.

---

```
```
