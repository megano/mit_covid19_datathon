# COVID-19 Health Data Coverage Analysis: MIT Datathon 2020

My individual contributions to the datathon's Track C. Our team analyzed gaps in how U.S.
states reported COVID-19 mortality data, and which structural and socioeconomic factors
correlated with worse outcomes.

## My Contribution

I analyzed how consistently states were reporting COVID-19 mortality data broken down by
population subgroup, and built a state-level choropleth map showing where reporting was
complete versus incomplete. Built on the [COVID Racial Data Tracker](https://covidtracking.com/race).

You can't understand who a public health crisis is harming if the data on who is affected
isn't being collected. That is what the coverage map is about.

Key outputs:
- [`eda/eda_race_coverage_map.ipynb`](eda/eda_race_coverage_map.ipynb): analysis notebook
- [`images/race_coverage_percent_by_state.png`](images/race_coverage_percent_by_state.png): state-level coverage map
- [`slides/TrackC-Team7.pdf`](slides/TrackC-Team7.pdf): team final presentation

## Teammates

- Kristin Mussar: disparity factor analysis (eda folder, KM_ files)
- Bing Han: literature review
- Timothy Sokphat: presentation deck

Mentors: Michael Williams (PACE Healthcare Capital), Lauren Chambers (ACLU of Massachusetts)

## Research Questions

- How complete is COVID-19 mortality reporting by population subgroup across U.S. states?
- What socioeconomic and structural factors correlate most strongly with worse outcomes?

## Datathon Context

MIT's COVID-19 Datathon brought together 297 participants and 77 mentors from 44 countries,
across 47 teams in five research tracks (May 10 to 16, 2020). Our team worked in the health
outcomes track on data completeness and the structural determinants of mortality disparities.
The datathon is documented in a published write-up:
[MIT COVID-19 Datathon: data without boundaries (PMC7799368)](https://pmc.ncbi.nlm.nih.gov/articles/PMC7799368/).

## Federal Reporting Mandate

Weeks after the datathon, amid mounting pressure from lawmakers and national advocacy groups
like the ACLU, the U.S. Department of Health and Human Services (HHS) issued a federal mandate
requiring laboratories to report race and ethnicity data by Aug 1, 2020.

## Full Project

This repo holds my individual contributions. The complete team project from the 2020
datathon, including the recorded presentation and interactive Tableau map, lives in the
original team repo: [kmussar/covid19_datathon](https://github.com/kmussar/covid19_datathon).
