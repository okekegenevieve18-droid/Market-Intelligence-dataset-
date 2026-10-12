# Market Intelligence Dataset

A sanitized, public-safe multi-sheet dataset prepared for data cleaning, exploratory analysis, visualization, and portfolio demonstrations.

The repository brings together research on competitors, companies, foundations, learning providers, market demand, digital platforms, and professional communities.

## Repository contents

```text
.
├── market-intelligence-dataset-sanitized.xlsx
├── SANITIZATION_REPORT.md
├── README.md
└── data/
    ├── Competitor_Research.csv
    ├── Company_Research.csv
    ├── Foundations.csv
    ├── Course_Catalogue.csv
    ├── Demand_vs_Supply.csv
    ├── Platform_Teardown.csv
    └── Career_Communities.csv
```

## Dataset sheets

| Sheet | Description |
|---|---|
| `Competitor_Research` | Competitor categories, public websites, activity measures, content patterns, and engagement metrics. |
| `Company_Research` | Company profiles, industries, business signals, hiring information, and public activity fields. |
| `Foundations` | Foundation profiles, focus areas, funding information, eligibility details, and application timelines. |
| `Course_Catalogue` | Training providers, courses, skill categories, delivery modes, durations, prices, and enrollment signals. |
| `Demand_vs_Supply` | Skill supply, pricing, learner demand, employer demand, market gaps, and opportunity indicators. |
| `Platform_Teardown` | Public platform features, access models, product observations, pricing information, and usability indicators. |
| `Career_Communities` | Professional communities, platforms, locations served, audience information, events, and activity characteristics. |

## Available formats

- Use the Excel workbook when you want all sheets in one file.
- Use the CSV files for Python, SQL, R, Excel, Power BI, or other analysis workflows.

Example using Python:

```python
import pandas as pd

competitors = pd.read_csv("data/Competitor_Research.csv")
print(competitors.head())
```

## Privacy and sanitization

This repository contains a sanitized public copy. The public version excludes:

- Contributor and verifier names
- Personal contact names, email addresses, and phone numbers
- Direct personal or profile links
- Internal organization-specific comparisons
- Internal outreach copy and recommendation fields
- Internal workstream identifiers and restricted source links
- Workbook comments, hyperlinks, hidden-source metadata, and original document properties

The original restricted workbook and private source links are not included in this repository.

## Data quality notes

- Values were collected from public-facing sources and may change over time.
- Some records contain missing values or statements such as `Not publicly verified`.
- Dates, prices, audience figures, hiring signals, and platform features should be rechecked before being used for business decisions.
- The dataset is intended for analysis and demonstration, not as a guaranteed-complete directory or verified market register.

## Suggested project ideas

- Compare competitor activity and engagement patterns.
- Identify skills with high employer demand and limited training supply.
- Analyze course pricing by skill category, level, or delivery mode.
- Explore foundation focus areas and funding mechanisms.
- Compare platform features and monetization models.
- Map professional communities by region, platform, and event activity.
- Build dashboards showing market gaps, training supply, or competitor trends.

## License and redistribution

No open-source license is currently applied. Public use and redistribution remain subject to confirmed data-ownership and permission requirements.

## Maintainer

- LinkedIn: https://www.linkedin.com/in/chiomaricha-okeke-a00a7436a
- GitHub: https://github.com/okekegenevieve18-droid
- X: https://x.com/her_voice76438?s=11
