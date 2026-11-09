# Indonesia's 2026 Forest and Land Fires: Environmental Evidence, Media Framing, and Government Response

> An interdisciplinary research project examining how Indonesia's 2026 forest and land fires were observed, reported, and governed across Sumatra, Kalimantan, and southern Papua.

**Project status:** Work in progress · **Study period:** 2026 (exact analysis window to be documented)

## Overview

Forest and land fires are simultaneously environmental events, public narratives, and governance challenges. Satellite observations can document where and when fire activity and smoke occurred. News reporting shapes how causes, impacts, responsibilities, and solutions are discussed. Government documents and operational records show how authorities defined risks, communicated priorities, and responded.

This project brings these evidence streams together to investigate **the relationship between environmental conditions, media framing, and government responses** during Indonesia's 2026 fire season.

Rather than focusing solely on which fires received the most attention, the study investigates **how government and media accounts converge, differ, or contest one another**, and how those accounts compare with **documented government actions and independently observed environmental conditions**.

## Research objectives

1. **Reconstruct environmental conditions:** Map the spatial and temporal development of fire activity, burned areas, haze transport, and air pollution in the study regions.
2. **Examine government response:** Review prevention and management policies, official communications, and documented interventions, including suppression, enforcement, and coordination.
3. **Analyze media framing:** Compare Indonesian, neighboring-country, and international news coverage of the fires, including explanations of causes, consequences, responsibility, and proposed solutions.
4. **Integrate the evidence:** Examine agreements, discrepancies, and changes over time among satellite observations, government narratives and actions, and media framing.

## Research questions

**Main question**

> How did government responses and media framing of Indonesia's 2026 forest and land fires align, diverge, and evolve in relation to observed environmental conditions?

**Supporting questions**

- **RQ1 — Environmental dynamics:** How did fire activity, burned area, haze, and atmospheric pollution vary across Sumatra, Kalimantan, and southern Papua and over time?
- **RQ2 — Government response:** How did relevant institutions define and respond to the fires through policy, prevention, emergency operations, enforcement, coordination, and public communication?
- **RQ3 — Media framing:** How did Indonesian, neighboring-country, and international news outlets frame causes, impacts, responsibility, government performance, and potential solutions?
- **RQ4 — Cross-source comparison:** Where did government narratives and actions converge with or diverge from media framing, and how did these patterns relate to observed fire and haze episodes?

## Analytical framework

The project distinguishes four types of evidence:

| Evidence stream | What it represents | Example indicators or records |
| --- | --- | --- |
| **Environmental observations** | Physical characteristics and development of fire and haze events | Satellite fire detections, burned-area estimates, land cover, smoke/aerosol observations, air-quality measurements |
| **Official narratives** | How government institutions describe the problem and their response | Press releases, speeches, advisories, reports, official explanations |
| **Documented government actions** | What authorities can be shown to have done | Operational deployments, regulations, budget or resource records, enforcement actions, coordination and incident logs |
| **Media framing** | How news outlets characterize the crisis and responses | News articles, headlines, attributed claims, quoted sources, problem/cause/responsibility/solution frames |

The integrated analysis focuses on **two connected comparisons**:

1. **Government narratives ↔ media frames:** How the crisis is defined, explained, evaluated, and contested.
2. **Documented government actions ↔ environmental observations:** When and where interventions occurred relative to observed fire and pollution conditions.

These comparisons are contextualized by location, land-cover type, transboundary impacts, and phase of the fire episode. The project does **not** assume that media reporting directly causes policy changes or that changes in satellite indicators alone prove whether an intervention was effective.

## Study areas

- **Kalimantan** — Fire dynamics, haze movement, and responses with possible transboundary dimensions.
- **Sumatra** — Fire and haze episodes in relation to land management, prevention, and emergency governance.
- **Southern Papua** — Fire patterns in distinct ecological and land-cover contexts and the corresponding responses and narratives.

Geographical boundaries, selected provinces/districts, and event inclusion criteria will be recorded in the methodology documentation.

## Methods and workflow

1. **Identify fire and haze episodes.** Process environmental datasets to construct spatial and temporal event profiles. Where possible, distinguish active-fire detections from burned area and satellite aerosol indicators from surface-level pollution exposure.
2. **Build a response chronology.** Collect policies, announcements, and corroborated operational records. Code official *statements* separately from documented *actions*.
3. **Compile and code news coverage.** Record publication date, outlet and country, geography, sources quoted, and frames concerning the problem, causes, responsibility, consequences, and solutions.
4. **Match evidence by episode.** Connect observations, official records, and news items using an explicit location and time window, while allowing for smoke transport beyond fire-origin areas.
5. **Compare across cases and phases.** Analyze patterns within and across Sumatra, Kalimantan, and southern Papua, including early warning, escalation, peak response, and aftermath where data are available.

### Shared framing dimensions

| Dimension | Guiding question |
| --- | --- |
| Problem definition | What is presented as the principal problem or risk? |
| Causal attribution | What factors are identified as causing or intensifying the fires? |
| Responsibility and accountability | Which actors are assigned duties or blamed, defended, or challenged? |
| Response and proposed solutions | What actions are implemented, announced, recommended, or criticized? |
| Consequences and evaluation | Which environmental, health, economic, and diplomatic impacts are recognized, and how are responses assessed? |

## Repository layout (proposed)

The initial repository contains this README and Git ignore rules. Existing GDELT
data and exploratory work are retained locally in
`archive/gdelt_indonesia_wildfire_2026/`; the archive is excluded from Git and is
not included in GitHub clones. The structure below describes planned work.

```text
.
├── README.md
├── data/
│   ├── raw/                 # Source data; may be excluded from Git
│   ├── interim/             # Harmonized or intermediate files
│   └── processed/           # Analysis-ready derived datasets
├── docs/
│   ├── methodology.md       # Sampling, matching, and analysis decisions
│   ├── data_sources.md      # Sources, dates, licenses, and access methods
│   └── codebook.md          # Media and government-response coding guide
├── notebooks/              # Exploratory and integrated analyses
├── src/                    # Reusable preprocessing and analysis scripts
├── outputs/
│   ├── figures/
│   └── tables/
└── references/             # Bibliography and source metadata
```

*This is a suggested structure, not a claim that these directories or scripts already exist. Adapt it to the repository's actual contents.*

## Data sources and provenance

A complete list of environmental products, news outlets, official institutions, time coverage, resolution, access links, licenses, and processing steps will be maintained in [`docs/data_sources.md`](docs/data_sources.md) once that file is created.

Potential source categories include:

- Satellite active-fire and burned-area products
- Aerosol, smoke-transport, and air-quality observations or model outputs
- Indonesian national and subnational regulations, reports, and operational records
- News coverage from Indonesia, neighboring countries, and international outlets

**Data handling:** Do not commit restricted datasets, full copyrighted news articles, sensitive personal data, or large raw satellite files without appropriate rights and safeguards. Prefer reproducible retrieval instructions, metadata, derived indicators, and appropriately licensed excerpts.

## Reproducibility and research safeguards

- Record the **exact temporal cutoff** and the spatial boundaries used in each analysis.
- Keep original source material and subsequent transformations traceable.
- Document inclusion criteria for events, policies, outlets, and articles.
- Differentiate **hotspot detections**, **burned area**, **aerosol/smoke indicators**, and **ground-level exposure**.
- Separate **official claims**, **documented actions**, **journalistic interpretations**, and **environmental observations** in the dataset and results.
- Record uncertainty, missing coverage, satellite limitations, and disagreement between sources.
- Avoid causal claims about policy effectiveness or media influence without an appropriate identification strategy and corroborating evidence.

## Current status and next steps

- [ ] Finalize geographical boundaries and the 2026 analysis window
- [ ] Inventory and document datasets, sources, and permissions
- [ ] Define criteria for selecting and matching fire/haze episodes
- [ ] Create a media-framing and government-response codebook
- [ ] Construct an event-level chronology across all evidence streams
- [ ] Compare selected cases and produce integrated maps, timelines, and tables
- [ ] Document limitations and prepare research outputs

## Contributors, citation, and license

**Research team:** _To be added_

**How to cite:** _Add a `CITATION.cff` or preferred citation once authorship and publication details are confirmed._

**License:** _To be determined. Repository code, datasets, and text may require different licenses depending on their sources and redistribution rights._

---

*This README describes an ongoing research design. It does not present preliminary propositions as confirmed findings.*
