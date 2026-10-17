# Ames Housing: Roofs by Build Period

## Summary

The dataset contains 2,930 homes. Gable roofs are the most common style in each build period. Hip roofs account for a larger share in 1940–1969 and 2000 onward than in the other periods. Composite shingles are used on 2,887 homes (98.5%), so roofing material shows little variation across build periods.

## Roof style and material by period

| Build period | Homes | Gable | Hip | Other styles | Composite shingles |
|---|---:|---:|---:|---:|---:|
| Before 1940 | 481 | 420 (87%) | 38 (8%) | 23 (5%) | 480 (99.8%) |
| 1940–1969 | 848 | 614 (72%) | 212 (25%) | 22 (3%) | 824 (97.2%) |
| 1970–1999 | 818 | 698 (85%) | 108 (13%) | 12 (1%) | 802 (98.0%) |
| 2000 onward | 783 | 589 (75%) | 193 (25%) | 1 (<1%) | 781 (99.7%) |

Percentages are within each build-period group. Style counts include all homes; “Other styles” combines every style except gable and hip.

## Roof style visualization

Each block represents approximately 5 percentage points.

```text
Gable roofs
Before 1940    █████████████████  87%
1940–1969      ██████████████     72%
1970–1999      █████████████████  85%
2000 onward    ███████████████    75%

Hip roofs
Before 1940    ██                  8%
1940–1969      █████              25%
1970–1999      ███                13%
2000 onward    █████              25%
```

## Roof material counts

| Roof material | Homes |
|---|---:|
| Composite shingle (`CompShg`) | 2,887 |
| Tar and gravel (`Tar&Grv`) | 23 |
| Wood shake (`WdShake`) | 9 |
| Wood shingles (`WdShngl`) | 7 |
| Roll | 1 |
| Metal | 1 |
| Membrane | 1 |
| Clay tile | 1 |
| **Total** | **2,930** |

### Roof material visualization

```text
Composite shingle  █████████████████████████████████████████████████  2,887 (98.5%)
Tar and gravel     ▏                                                23 (0.8%)
Wood shake         ▏                                                 9 (0.3%)
Wood shingles      ▏                                                 7 (0.2%)
Roll               ·                                                 1 (<0.1%)
Metal              ·                                                 1 (<0.1%)
Membrane           ·                                                 1 (<0.1%)
Clay tile          ·                                                 1 (<0.1%)
```

## Plain-language interpretation

Gable roofs are the leading style across all four construction periods. Hip roofs are relatively more common among homes built in 1940–1969 and from 2000 onward. Composite shingles dominate the material choices throughout the dataset: 98.5% of all homes have them, and every period is at least 97% composite shingle. These are associations in this dataset and do not establish why a roof type or material was chosen.

## Data and method

Source file: `AmesHousing-1.csv` in the project workspace. The requested filename `AmesHousing.csv` was not present; `AmesHousing-1.csv` was used as the available Ames Housing data file. Build periods are grouped as before 1940, 1940–1969, 1970–1999, and 2000 onward. Roof style and material labels are taken from the source columns `Roof Style` and `Roof Matl`.
