# Analysis of COVID-19 Impact and GDP Per Capita (2020-2022)

## Introduction
The COVID-19 pandemic affected countries differently, not only in terms of health outcomes but also economic impact. This report explores:

- How GDP per capita correlates with COVID-19 cases and deaths.
- Whether economic status played a role in pandemic severity.
- Trends in economic recovery post-pandemic.
The dataset includes 177 countries with yearly data on GDP per capita, COVID-19 cases, and deaths.

## Raw Data Overview

### COVID-19 data
- Active Cases
- Cumulative Cases
- Cumulative Deaths
- Daily New Cases
- Daily New Deaths

### GDP per Capita data
- Country Name
- Country Code
- Indicator Name
- Indicator Code
- Year
- GDP per Capita

## Key Findings
### COVID-19 Impact: Cases & Deaths

Countries with larger populations generally had higher total case counts. The number of daily new cases and deaths peaked in 2021, followed by a decline in 2022, in that same year, we can see fatality rates varied significantly across countries due to healthcare quality and government interventions.

GDP per capita slightly increased from 2020 to 2022, which suggests economic recovery post-pandemic.

![covid deaths   cases](https://github.com/user-attachments/assets/5034b857-22fe-44b1-92ec-ca6610a94ff6)

Cases peaked in 2021, followed by a decline in 2022. Deaths also peaked in 2021, showing a lagging impact of severe cases. The decline in 2022 are attributed to improvement in treatments, vaccinations, social distancing.

### Correlation analysis between GDP per capita and COVID-19 impact:

I was able to see a negative correlation around -0.2 to -0.3 between GDP per capita and COVID cases & deaths, indicating a strong negative relationship, this means that as GDP per capita increases, COVID impact decreases.

![output](https://github.com/user-attachments/assets/fdec0706-dd8e-4b43-bebb-c075668df112)


### Covid-19 Deaths VS GDP per Capita.
![GDP VS Covid-19 Deaths](https://github.com/user-attachments/assets/22f3b38d-e120-47d7-a376-fedad37139e9)

Many countries is observed near the lower left of the graph, which indicates a low total amount of deaths and low GDP per capita. This suggests that many countries, particularly lower-income ones, experienced relatively fewer Covid-19 deaths in absolute numbers.

The spread increases as we move from 2020 to 2022, indicating cumulative deaths rose with time across most countries.

### GDP per Capita VS Covid-19 Cases.

![GDP per Capita VS Covid-19 Cases](https://github.com/user-attachments/assets/ccf97800-eb61-4f66-aed9-0c5d481dfc8b)

The majority of countries cluster on the lower left, indicating low GDP per capita with varying cumulative deaths. This suggests a strong concentration of lower-income countries with relatively lower death counts.

As GDP per capita increases, the distribution spreads out, but very few countries with high GDP per capita show extremely high cumulative deaths. This indicates that richer countries experienced varying levels of impact

Countries with very high GDP per capita (above $100,000) mostly have lower cumulative deaths, which highlights better healthcare systems and pandemic management.

### Covid-19 Cases VS Covid-19 Deaths.

![Covid deaths vs cases](https://github.com/user-attachments/assets/a1e8c8c9-316d-4283-b843-b3722b863eae)

The plot shows a correlation between total cases and total deaths. This means that countries with a higher number of Covid-19 cases also tend to have a higher number of deaths, which is expected.

A significant group is visible in the lower-left corner, representing countries with relatively low total cases and deaths. These are countries with smaller populations, effective pandemic management, and underreporting.
