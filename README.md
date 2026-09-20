# CITS2402 Project — Household Composition & Weekly Rent: Australia vs New Zealand
(In Partial Fulfillment to Unit Code CITS2402 - Introduction to Data Science)

## Overview

This project compares household/family composition and weekly rent between Australia (2021 Census) and New Zealand (2023 Census), examining whether housing cost burden differs across household types and whether this pattern is consistent between the two countries.

## Aim

This report aims to examine the relationship between household/family composition and housing affordability in Australia and New Zealand, using weekly rent as a key affordability indicator. As housing costs continue to rise in both countries, understanding which household types bear the greatest rental burden — and whether this burden is distributed similarly across both nations — offers insight into broader social and economic pressures shaping each country's housing landscape.

## Research Questions

1. **RQ1:** How does median weekly rent differ across household/family types (e.g., couple-only, couple-with-children, one-parent, lone-person, group households) in Australia (2021) and New Zealand (2023), and which household types face the highest and lowest rent burdens in each country?
2. **RQ2:** How does this rent-by-household-type pattern vary regionally (e.g., major cities vs. regional/rural areas) within each country, and which household types show the greatest rent disparity between urban and regional areas?
3. **RQ3:** Do household types with higher shares in urban areas (from RQ2) also face disproportionately higher rent burdens — and is this relationship consistent between Australia and New Zealand, or does it diverge?

## Data Sources

### Australia — 2021 Census
- **Source:** Australian Bureau of Statistics (ABS)
- **Variables:** Household Composition (HHCD) × Rent (weekly) (RNTRD)
- **Note:** <placeholder>

### New Zealand — 2023 Census
- **Source:** Stats NZ
- **Tool used:** Aotearoa Data Explorer
- **Variables:** Household composition × Weekly rent paid by household
- **Portal:** https://explore.data.stats.govt.nz
- **Topic tables reference:** https://www.stats.govt.nz/2023-census/find-topic-tables-from-the-latest-2023-census-releases/

## Data Files

*(List actual filenames and their contents here once finalized, e.g.)*
- `au_household_rent_2021.csv` — Australia: household composition × rent (weekly), [geography level]
- `nz_household_rent_2023.csv` — New Zealand: household composition × weekly rent, [geography level]

## Known Data Considerations

- **Timing gap:** Australian data is from 2021; New Zealand data is from 2023 — a 2-year gap that should be acknowledged when interpreting cross-country differences.
- **Confidentiality perturbation:** Both ABS and Stats NZ apply small random adjustments to cell values to protect respondent confidentiality. Totals may not sum exactly as a result.
- **Category reconciliation:** Household composition categories differ slightly in wording/definition between the two countries (see report Section [X] for the full mapping table used).
- **No direct pre-built cross-tab:** the Household Composition × Rent table for Australia was built manually via TableBuilder, since no equivalent pre-packaged DataPacks table exists.

## Team

- Joseph
- Cody
- Tomas

## Project Structure

```
├── README.md
├── CITS2402-Project-[STUDENTNO1]-[STUDENTNO2].ipynb
├── CITS2402-Project-[STUDENTNO1]-[STUDENTNO2].pdf
├── data/
│   ├── au_household_rent_2021.csv
│   └── nz_household_rent_2023.csv
```
