# Denmark SARS-CoV-2 Phylogeography

Phylogeographic analysis of SARS-CoV-2 lineages in Denmark with ancestral **division-level** location reconstruction across the 5 Danish regions: Hovedstaden, Midtjylland, Nordjylland, Sjaelland, and Syddanmark.

## View Builds

| Lineage | Pango | Sequences | Date Range | Link |
|---------|-------|-----------|------------|------|
| **Alpha** | B.1.1.7 | 6,372 | Jan 4 – Jun 2, 2021 | [View](https://nextstrain.org/community/leke-lyu/denmark-ncov/Denmark/Alpha) |
| **Delta** | AY.\*/B.1.617.2 | 6,595 | Jun 7 – Sep 5, 2021 | [View](https://nextstrain.org/community/leke-lyu/denmark-ncov/Denmark/Delta) |
| **Omicron** | BA.1/BA.2 | 8,571 | Nov 22 – Dec 28, 2021 | [View](https://nextstrain.org/community/leke-lyu/denmark-ncov/Denmark/Omicron) |

## Methodology

- **Sampling**: Sequences are proportionally subsampled per (variant, epiweek, region) to ensure equal sampling rates across all 5 regions. Sampling rates: Alpha 8%, Delta 12%, Omicron 4% of detected cases per region per epiweek (minimum 1 sequence per stratum, random seed 42).
- **Ancestral reconstruction**: Division-level mugration with no sampling bias correction, since sampling rates are already balanced across regions.
- **Outgroup**: Wuhan/Hu-1/2019 used for rooting all builds.
- **Data source**: [GISAID](https://www.gisaid.org/)

## Built with

[Nextstrain](https://nextstrain.org/) ncov workflow — [github.com/nextstrain/ncov](https://github.com/nextstrain/ncov)
