# AquaEPIC — SRS Expert Elicitation Study

**Expert prioritisation of disease control measures in Scottish Atlantic salmon farming**

> Royal (Dick) School of Veterinary Studies · University of Edinburgh  
> Division of Global Agriculture and Food Systems · AHW Cluster Pump-Priming Programme

🌐 **Live site:** [fomedi.github.io/aquaepic](https://fomedi.github.io/aquaepic/)  
📋 **Expert ballot:** [fomedi.github.io/aquaepic/ballot.html](https://fomedi.github.io/aquaepic/ballot.html)

---

## About this study

This project applies a structured expert elicitation approach — a modified Delphi method — to identify and prioritise disease control measures for Piscirickettsiosis (*Piscirickettsia salmonis*, SRS) in Scottish Atlantic salmon aquaculture. The study is funded by the **Animal Health and Welfare (AHW) Cluster Pump-Priming Programme** at the University of Edinburgh and is connected to the **AquaEPIC initiative**, a proposed science–policy–industry interface for aquaculture health governance in Scotland.

Experts rate each shortlisted measure on two independent dimensions:
- **Effectiveness** (0–4 scale) — perceived impact on SRS control
- **Feasibility** (0–4 scale) — ease of implementation under Scottish conditions

Results feed into a 2×2 priority matrix: **Act Now / Enable / Reconsider / Deprioritise**.

---

## Study phases

| Phase | Description | Timeline |
|-------|-------------|----------|
| **1** | List building & instrument design with industry representatives | May 2026 |
| **2** | Screening ballot — panel votes to shortlist ≤35 measures | June 2026 |
| **3** | Modified Delphi ranking — two rounds of dual scoring | June–July 2026 |
| **4** | Easter Bush in-person synthesis workshop | October 2026 |

Target manuscript submission: **Journal of Fish Diseases, July 2026**

---

## Repository contents

| File | Description |
|------|-------------|
| `index.html` | Project website — about, team, phases, literature, participation, ballot access |
| `ballot.html` | Expert screening ballot — open access, submits to Google Sheets |
| `Code.gs` | Google Apps Script — receives ballot and consent responses, writes to Google Sheets |
| `README.md` | This file |
| `fm.jpg` | Photo — Fernando O. Mardones *(add to repo when available)* |
| `jdp.jpg` | Photo — Jorge del Pozo *(add to repo when available)* |
| `ka.jpg` | Photo — Katie Adams *(add to repo when available)* |
| `dp.jpg` | Photo — Davide Pagnossin *(add to repo when available)* |

---

## Research team

| Name | Role | Contact |
|------|------|---------|
| **Fernando O. Mardones** | Principal Investigator | [fmardone@ed.ac.uk](mailto:fmardone@ed.ac.uk) · [Profile](https://edwebprofiles.ed.ac.uk/profile/fomardones) |
| **Jorge del Pozo** | Co-investigator | [Jorge.Del.Pozo@ed.ac.uk](mailto:Jorge.Del.Pozo@ed.ac.uk) · [Profile](https://edwebprofiles.ed.ac.uk/profile/dr-jorge-del-pozo) |
| **Katie Adams** | Co-investigator | [kadam3@exseed.ed.ac.uk](mailto:kadam3@exseed.ed.ac.uk) · [Profile](https://www.epicscotland.org/people/dr-katie-adam/) |
| **Davide Pagnossin** | EPIC Research Fellow | [dpagnoss@ed.ac.uk](mailto:dpagnoss@ed.ac.uk) · [Profile](https://www.epicscotland.org/people/dr-davide-pagnossin/) |

---

## Technical setup

### Adding team photos
Upload square JPG files to the root of this repository with these exact names:
`fm.jpg`, `jdp.jpg`, `ka.jpg`, `dp.jpg`

They will appear automatically in the team section of the website — no code changes needed.

### Google Sheets integration
The ballot and consent form submit responses to a Google Sheet via Apps Script.

1. Open the linked Google Sheet → **Extensions → Apps Script**
2. Paste the contents of `Code.gs`
3. Run `setupSheet()` and `setupConsentSheet()` once to create the response tabs
4. Deploy as a **Web App** (Execute as: Me · Access: Anyone)
5. The web app URL is already embedded in `ballot.html` and `index.html`

### Updating the live site
Upload changed files directly to this repository. GitHub Pages republishes automatically within ~1 minute.

---

## Ethics & data

- Ethical approval: University of Edinburgh (pending, to be obtained prior to data collection)
- Data stored securely on University of Edinburgh systems in accordance with UK GDPR
- Participant responses anonymised before analysis
- Data retained for up to 5 years then securely deleted

---

## Funding & affiliation

Funded by the **Animal Health and Welfare Cluster Pump-Priming Programme**, Royal (Dick) School of Veterinary Studies, University of Edinburgh.

Connected to the **AquaEPIC initiative** — a proposed Centre of Expertise in Aquaculture Health Policy inspired by the EPIC Scotland model for terrestrial animal disease governance.

---

*Last updated: May 2026*
