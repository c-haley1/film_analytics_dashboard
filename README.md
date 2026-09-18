# Film Analytics Strategy (Tableau)

**[View the live dashboard on Tableau Public →](https://public.tableau.com/app/profile/colin.haley/viz/FinalProject_17857094663200/FilmAnalyticsStrategy)**

An interactive Tableau dashboard built to answer a hypothetical Netflix greenlighting question: what combination of genre, budget, runtime, rating, and setting gives a film the best odds of being both highly profitable and a strong return on investment — using data on 200+ of the highest-rated and most profitable films from 1989–2014.

## Objective

Determine the requirements Netflix should use for its next film to maximize the odds of high profitability and a strong return on investment (ROI).

## Data

Sourced from **IMDb.com**, covering 200+ of the highest-rated and most profitable films released between 1989 and 2014, including:

- Genre, MPAA rating, release year/decade/month
- Budget ($), gross ($), profit ($), ROI (%)
- Runtime (minutes) and runtime category
- IMDB rating and rating count
- Budget tier, franchise/sequel status and franchise name
- Filming setting (city, state, country)

## Methodology

Profitability and ROI were analyzed across three strategic lenses:

1. **Genre Strategy** — which genres deliver the best profit and ROI
2. **Budget & Financial Predictors** — how budget size and tier relate to ROI and profit
3. **Creative Blueprint** — how runtime, rating, and filming setting relate to financial success

## Dashboard Pages

**Film Analytics Strategy** (main navigation dashboard, flips between the pages below)

**Genre Strategy**
- Dynamic Genre Ranking (ranks genres by a user-selected metric)
- Genre Lollipop (average profit by genre)
- Gross vs. ROI by Genre Groups
- MPAA Rating × Genre heat map

**Budget and Financials**
- Optimal Budget Range (budget vs. average ROI)
- Profits by Year (profit trend over time)
- ROI by Budget Tier (pie)

**Creative Blueprint**
- Filming Setting map
- Profitability Opportunity Matrix (IMDB rating vs. gross)
- Runtime vs. average profit
- Runtime vs. Rating "sweet spot" grid

**Text Supplement** — narrative write-up of the analysis (see findings below)

## Board Recommendations / Film Guidelines

Based on the combined analysis, the recommended profile for Netflix's next film:

| Attribute | Recommendation |
|---|---|
| Genre | Fantasy |
| MPAA Rating | PG-13 |
| Budget Tier | Mid-tier ($40–$80 million) |
| Optimal Budget | Under $100 million |
| Runtime | ~2 hours |
| Filming Setting | Pennsylvania |
| Expected ROI | At least 10% |
| Expected Gross | $700 million |
| Expected Profit | $600 million |
| Expected IMDB Rating | 7.5–8.0 |

## Conclusion

Building a film to this profile is expected to achieve both the highest profit and the strongest potential return on investment for Netflix. These guidelines were derived from in-depth analysis of over 200 of the most popular and profitable films in IMDb's database, combining genre, budget, and creative (runtime/rating/setting) analytics into a single set of production guardrails.

## Repo Contents

| File | Description |
|---|---|
| `Final_Project.twbx` | Full packaged Tableau workbook — data source, all worksheets, and all dashboards |

## Tools

Tableau · IMDb film data

## Author

Colin Haley — July 2026
