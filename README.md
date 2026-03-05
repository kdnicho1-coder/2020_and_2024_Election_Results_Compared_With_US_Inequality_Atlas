# 2020_and_2024_Election_Results_Compared_With_US_Inequality_Atlas
Exploratory analysis of county vote share changes between the 2020 and 2024 U.S. presidential elections. Election data is merged with the US Inequality Atlas to examine whether county-level inequality indicators correlate with shifts in voting patterns.


**County Inequality and U.S. Presidential Election Change (2020–2024)**

**Overview**

This project explores how county-level inequality might relate to changes in voting patterns between the 2020 and 2024 U.S. presidential elections.

I pulled county election results for both elections and calculated the change in vote share from 2020 to 2024. I then merged those results with the US Inequality Atlas, which includes county-level indicators such as poverty rates, unemployment, income inequality, and access to resources.

The goal of this project is exploratory. I wanted to see whether counties experiencing higher levels of structural inequality showed any measurable patterns in how voting shifted between the two elections.

Research Question:
Do county-level inequality indicators correlate with changes in vote share between the 2020 and 2024 U.S. presidential elections?

**Data Sources**

County Election Results (2020) - https://www.kaggle.com/code/mahmoudredagamail/ultimate-us-election-dataset
County Election Results (2024) - https://github.com/tonmcg/US_County_Level_Election_Results_08-24
County-level vote totals and vote share were used to calculate how voting patterns changed between the two elections.

US Inequality Atlas by County - https://www.kaggle.com/datasets/lucassteuber/us-inequality-atlas
This dataset provides county-level indicators such as poverty, unemployment, income inequality, and other structural measures. These indicators were used to examine whether broader economic and social conditions relate to election shifts.

**Methods**

The analysis follows a straightforward process:

Load county election data for both elections

Calculate the change in vote share between 2020 and 2024

Merge election results with the inequality dataset using county FIPS codes

Clean and inspect the merged data

Explore relationships between inequality indicators and vote share change using correlation analysis and visualizations

All analysis was completed in a Google Colab notebook using Python.

**Tools**

**Python libraries used in the project include:**

pandas

numpy

matplotlib

seaborn

scipy
