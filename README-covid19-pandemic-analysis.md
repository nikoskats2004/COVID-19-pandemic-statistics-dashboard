# COVID-19 Pandemic Analysis Dashboard

**File:** `Μελέτη - ανάλυση της πανδημίας COVID-19.pbix` *(Greek: "Study – analysis of the COVID-19 pandemic")*

## Overview

A Power BI report analyzing global, country-level **COVID-19 pandemic statistics** — case counts, deaths, recoveries, and critical cases — built as a coursework study on the pandemic.

## Data model

Single table, `Table 1`, with columns:

| Column | Description |
|---|---|
| `Country, Other` | Country / region name |
| `Total Cases` | Cumulative confirmed cases |
| `New Cases` | Newly confirmed cases |
| `Active Cases` | Currently active cases |
| `Serious, Critical` | Cases in serious/critical condition |
| `Total Recovered` | Cumulative recoveries |
| `Total Deaths` | Cumulative deaths |

## Report pages

- **Page 1** (9 visuals) — a country slicer, 4 KPI cards, a donut chart, a column chart, a bar chart, plus an additional card
- **Page 2** (7 visuals) — a country slicer, 5 KPI cards, and a map showing the geographic distribution of cases
- **Page 3** — empty/placeholder page

The report also includes a **Linguistic Schema**, which enables Power BI's natural-language **Q&A** feature over the dataset.

## Use case

Exploratory analysis of COVID-19 epidemiological data at the country level — created as a data-visualization/BI coursework assignment.

## Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).

## How to open

Open the `.pbix` file in Power BI Desktop and use the country slicer on Page 1 or Page 2 to filter the dashboard, or try the built-in **Ask a question** (Q&A) box.

## Data disclaimer

Figures reflect a specific data snapshot and are **not** updated in real time; they should not be used for current public-health decision-making.
