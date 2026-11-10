# south-korea-renewable-energy-analysis
# South Korea Renewable Energy & Economic Analysis (2015–2024)

## Overview

This project examines the relationship between renewable electricity adoption, electricity generation patterns, carbon intensity, and economic growth in South Korea from 2015 to 2024.

Using Python, publicly available economic and energy datasets, and statistical analysis, the project investigates how South Korea's changing electricity mix coincided with environmental and economic trends.

## Research Question

To what extent has renewable energy adoption in South Korea been associated with changes in electricity generation, carbon intensity, and economic growth?

## Key Findings

- **Renewable electricity adoption increased:** Renewable electricity's share of generation rose from 2.77% in 2015 to 9.71% in 2024.
- **Coal's share declined:** Coal fell from 42.48% to 30.51% of electricity generation.
- **Electricity carbon intensity decreased:** Carbon intensity declined by 14.79% over the study period.
- **Economic growth continued:** Real GDP increased by 24.56% between 2015 and 2024.
- **Renewables and carbon intensity were strongly negatively correlated:** Pearson's *r* = −0.8819 (*p* = 0.0007; n = 10).
- **GDP growth and renewable adoption:** The observed correlation was not statistically significant at the 5% level.

These findings describe associations, not proof of causation.

## Visualizations

### 1. Renewable Electricity Adoption

![Renewable Electricity Adoption](figures/Figure_1_Renewable_Electricity_Adoption.png)

### 2. Electricity Generation Mix

![Electricity Generation Mix](figures/Figure_2_Electricity_Generation_Mix.png)

### 3. Renewable Electricity vs. Carbon Intensity

![Renewables vs Carbon Intensity](figures/Figure_3_Renewables_vs_Carbon_Intensity.png)

### 4. Economic Growth vs. Carbon Intensity

![Economic Growth vs Carbon Intensity](figures/Figure_4_Economic_Growth_vs_Carbon_Intensity.png)

### 5. Electricity Sources vs. Carbon Intensity

![Electricity Sources vs Carbon Intensity](figures/Figure_5_Electricity_Sources_vs_Carbon_Intensity.png)

## Methodology

The analysis uses annual observations from 2015 through 2024 and includes:

- Data collection and integration
- Data cleaning and validation
- Exploratory data analysis
- Pearson and Spearman correlation analysis
- Sensitivity analysis excluding 2020
- Trend analysis and data visualization

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab
- GitHub

## Repository Structure

```text
data/       Cleaned research dataset
figures/    Five research visualizations
notebooks/  Python research notebook
report/     Final research report (PDF)
```

## Limitations

This study uses a relatively small annual sample of ten observations. Correlation does not establish causation, and electricity generation shares are interdependent. The analysis focuses on electricity-sector carbon intensity rather than the entire economy's emissions.

## Future Research

Future work could incorporate additional years of data, energy prices, electricity demand, policy changes, investment trends, and more advanced statistical methods to better understand the economic and environmental dimensions of South Korea's energy transition.

## Research Period

2015–2024

## Author

Undergraduate research project Conducted by Cayden Miller.
