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

**Literature Review**
Voting patterns in the United States are often described as a divide between rural and urban areas. Research shows that this divide has become increasingly pronounced in recent elections. Albrecht (2022) analyzed county-level voting data from the 2016 and 2020 presidential elections and found that rural counties were far more likely to support Donald Trump, while urban counties overwhelmingly supported Democratic candidates. The study also found that counties with higher proportions of non-Hispanic white residents and lower levels of educational attainment were strong predictors of support for Trump (Albrecht, 2022).

Other research suggests that structural inequality and neighborhood conditions may influence long-term political participation. Using data from the Moving to Opportunity housing experiment, Elder, Enos, and Mendelberg (2024) examined whether growing up in disadvantaged neighborhoods affects voting behavior later in life. Their findings suggest that exposure to neighborhood poverty can shape political participation, although improvements in neighborhood conditions alone do not necessarily lead to increased voter turnout (Elder et al., 2024).

Geographic scale can also affect how voting behavior is interpreted. Mapes (2024) shows that county-level election data can mask important variation within counties. Using precinct-level data from the 2020 election, the study demonstrates that small towns often vote differently than surrounding rural areas. This suggests that analyzing voting behavior at larger geographic levels may hide important local differences.

Together, these studies highlight how geographic location, economic conditions, and demographic characteristics interact to shape voting behavior. Building on this research, this project examines whether county-level inequality measures are associated with changes in voting patterns between the 2020 and 2024 U.S. presidential elections.

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

References:
Albrecht, D. E. (2022). Donald Trump and changing rural/urban voting patterns. Journal of Rural Studies, 91, 148–156. https://doi.org/10.1016/j.jrurstud.2022.02.009

Elder, E. M., Enos, R. D., & Mendelberg, T. (2024). The long-term effects of neighborhood disadvantage on voting behavior: The Moving to Opportunity experiment. American Political Science Review.

Google. (2026). Gemini [Large language model]. https://gemini.google.com For Code help and help with Github Repository

Mapes, J. (2024). Using big data to study small places: Small-town voting patterns in the 2020 U.S. presidential election. Growth and Change.

McGovern, T. (2024). U.S. county-level election results, 2008–2024 GitHub. https://github.com/tonmcg/US_County_Level_Election_Results_08-24

OpenAI. (2026). ChatGPT (GPT-5.3) [Large language model]. https://chat.openai.com - For code, grammar and figuring how to make this repository.

Reda, M. (2024). Ultimate U.S. election dataset. Kaggle. https://www.kaggle.com/code/mahmoudredagamail/ultimate-us-election-dataset

Steuber, L. (2024). U.S. inequality atlas. Kaggle. https://www.kaggle.com/datasets/lucassteuber/us-inequality-atlas


