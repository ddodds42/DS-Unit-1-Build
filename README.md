# Measuring Why Nations Fail

The book “Why Nations Fail” argues there are 3 core determinants of nations’ long-run success or failure: Economic Inclusivity, Political Inclusivity,and Sufficient state centralization. Do predictive metrics for these attributes of nation-states exist? Using open datasets and python, I will attempt to find such metrics.

Master_EDA_viz.ipynb is the main notebook for analysis and visualization of the final dataset, "Master13.csv".

TI_CPI_Pivot_test.ipynb enabled me to pivot the Transparency International and World Bank World Development Indicators into wide format by year.

HPI_merger.ipynb enabled be to merge together, by correct country name, the HPI data sets from 2006, 2009, 2012, and 2016.

Standardizer.ipynb enabled me to standardize, by mean and std. dev., two of the attributes: the Happy Planet index and the Corruptions Perceptioins index.

Imputer.ipynb enabled me to impute time interpolated values missing from each data series.

Nation_Names.ipynb expidited the matching of standard country codes to slightly divergent names for the same countries, which were not standard accross the 3 major source organizations.

Linear_Regressor.ipynb enabled me to synopsize each nation's mean value and change over time since 1972, for each attribute, into 2 variables, which were then merged into the final dataset for analysis in Master_EDA_viz.ipynb.
