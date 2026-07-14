# Report title

![Report overview](images/report-overview.png)

## Executive summary

In 2–4 sentences, explain the business problem, who used the report, what you built, and the most important outcome. Keep confidential values anonymized or use percentages.

## Business questions

- What decision should the report help someone make?
- Which KPIs show success or risk?
- What level of detail is needed to take action?

## Audience

Describe the intended users, such as sales leadership, finance analysts, or operations managers.

## Data

| Source | Contents | Refresh | Publicly shareable? |
|---|---|---|---|
| Example: synthetic CSV | Orders and products | Daily | Yes |

State the date range, approximate row count, quality issues, and any anonymization or synthetic-data method. Do not include credentials or private connection details.

## Solution

### Data preparation

Summarize the most meaningful Power Query transformations, validation rules, and data-quality handling.

### Data model

![Data model](images/data-model.png)

Describe the fact and dimension tables, relationship choices, date table, granularity, and any row-level security.

### Selected DAX

```DAX
Example Measure =
DIVIDE ( [Numerator], [Denominator] )
```

Explain why the measure matters. Add more measures in the `dax` folder when useful.

### Report experience

Describe navigation, filters, drill-through, tooltips, bookmarks, accessibility, mobile layout, and other purposeful UX choices.

## Key insights and actions

1. State an insight revealed by the analysis.
2. Connect it to a recommended business action.
3. Quantify impact where disclosure is allowed; otherwise use an indexed or percentage-based result.

## Challenges and lessons

Explain one or two genuine challenges, how you handled them, and what you would improve next.

## Files

- `images/` — sanitized report and model screenshots
- `dax/` — selected measures in plain text
- `sample-data/` — optional synthetic or public sample data

## Privacy

Confirm that the screenshots and files contain no personal data, confidential metrics, tenant details, credentials, or proprietary source data.

