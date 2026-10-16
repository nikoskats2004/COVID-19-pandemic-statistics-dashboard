# COVID-19 Pandemic Analysis Dashboard

An interactive **Power BI** report that explores country-level COVID-19 statistics — confirmed cases, active cases, deaths, recoveries and critical cases — built as a data-visualization / BI coursework study of the pandemic.

**File:** `Μελέτη - ανάλυση της πανδημίας COVID-19.pbix` (Greek: *"Study – analysis of the COVID-19 pandemic"*)

## Report pages

### Page 1 – Overview
- **Country slicer** – filters all visuals on the page by country.
- **5 KPI cards** – Total Cases (276K), Active Cases (173K), Total Deaths (11K), Total Recovered (91K) and Critical Cases (8,120).
- **Column chart** – the top 5 countries by Active Cases (Italy, Germany, USA, Spain, Iran).
- **Donut chart** – share of Active Cases (62.85 %), Total Recovered (33.02 %) and Total Deaths (4.13 %).
- **Stacked bar chart** – Total Cases, Active Cases, New Cases and Serious/Critical by country.

### Page 2 – Geographic distribution
- **Country slicer** with a *Select all* option.
- **5 KPI cards** – Total Cases, Active Cases, Total Deaths, Total Recovered and Serious/Critical.
- **Bubble map** – bubble size shows Total Cases per country; tooltips show Total Deaths, Total Recovered and Serious/Critical.

The report also includes a Linguistic Schema, which enables Power BI's natural-language **Q&A** feature over the dataset.

## Data model

A single table, `Table 1`, with one row per country/region:

| Column | Description |
|---|---|
| `Country, Other` | Country / region name |
| `Total Cases` | Cumulative confirmed cases |
| `New Cases` | Newly confirmed cases |
| `Active Cases` | Currently active cases |
| `Serious, Critical` | Cases in serious/critical condition |
| `Total Recovered` | Cumulative recoveries |
| `Total Deaths` | Cumulative deaths |
| `New Deaths` | Newly reported deaths |
| `Tot Cases/1M pop` | Total cases per 1 million population |

## Use case

Exploratory analysis of COVID-19 epidemiological data at the country level: comparing countries, seeing how cases split into active / recovered / deceased, and locating the most affected regions on a map.

## Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

## How to open

1. Download the `.pbix` file.
2. Open it in Power BI Desktop.
3. Use the country slicer on Page 1 or Page 2 to filter the dashboard, hover over the map bubbles for details, or try the built-in **Ask a question** (Q&A) box.

## Data disclaimer

Figures reflect a specific data snapshot and are **not updated in real time**. They must not be used for current public-health decision-making.
