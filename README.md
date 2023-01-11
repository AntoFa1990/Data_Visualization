# Data_Visualization
Python-based data visualization use-case based on a pharmaceutical lab study.

##Analysis
###Overview
Pymaceuticals, Inc. is a pharmaceutical company screening new treatments for squamous cell carcinoma (SCC), one of the most frequently occurring forms of skin cancer.

In this study, 249 mice identified with SCC tumors received treatment with several newly developed drug regimens. Over a 45 day period, tumor development was observed and measured, along with the sex, weight and age of the mice.

The purpose of this study was to measure the performance Pymaceutical's target drug, Capomulin, against that of the other treatment regimens.

###Description of Data
• Nine treatment drugs and one placebo were tested on 249 mice over a 45 day period.

• One mouse was removed from the dataset due to duplication.

• In the adjusted dataset of 248 mice, the ratio of males and females was virtually equal, with 50.4% vs. 49.6% respectively.

• The number of timepoint observations per drug during the period ranged from 148-230, indicating a robust sample size for the drugs tested.

###Summary Findings
• Over the 45-day testing period, Capomulin and Ramicane showed the smallest mean tumor volume, as well as the smallest standard deviation.

• Final tumor volume for four drugs (Capomulin, Ramicane, Infubinol, and Ceftamin) were further analyzed to determine the data distribution for each drug and the presence of any outliers.

• The median values and inter-quartile-ranges of the final tumor volumes of Capomulin and Ramicane were the lowest, again suggesting that these two drugs were the most effective.

• Of the four, only Infubinol was shown to have potential outliers.

• The Capomulin treatment data suggest a strong positive relationship exists between tumor size and mouse weight based on a Pearson correlation (r = 0.84).

• A linear regression model was also run on the Capomulin treatment data, with mouse weight as the independent variable and tumor size the dependent variable. The resulting R-squared of .70 indicates that mouse weight explains 70% of the variation in the observed tumor sizes.

• Despite initially positive findings, based on the Pearson correalation and linear regression R-squared, it is recommended that mouse weight be controlled for during future testing, to better isolate the impact of this variable.
