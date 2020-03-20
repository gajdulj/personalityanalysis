# 5 Personality Test- analysis of the results for European countries

Purpose: The aim of this analysis is to evaluate the trends in human personalities across different European countries.
Initial work focuses on cleaning the data, dimensionality reduction and identifying the aggregated trends. 
Additional contributions will be appreciated.

## Summary of the analysis

1. Is there any trend in personalities across European countries?
The average for all characteristics is near 3 on the 1 to 5 scale.
Highest variability measured by the standard deviation observed in emotional stability (σ=0.65).
Openness scored on average higher than other personality traits (μ=3.31).

2. Is there a link between different personality traits?
The strongest correlation identified for openness and consciousness: 0.33, as well as agreeableness and extraversion: 0.32.
Correlation between emotional stability and extraversion was significantly lower: 0.063.

3. Can UK citizens personality explain the unorthodox government response to COVID-19? (compare the results to Poland)
Survey responses suggest that British people score 6.9% higher on extraversion, 5.3% less on emotional stability and 4.8% lower on conscientiousness.

4. Can we predict where are you from based on your personality traits?
As we can see, the model scored 13.2% better than a random guess.

------
## libraries used:
* pandas
* matplotlib
* seaborn
* numpy
* collections (defaultdicst)
* xgboost
* sklearn
* graphviz
------
## files in the repository:
* personality_analysis.ipynb this is the file with analysis done so far
* codebook.txt this file explains the dataset source as well as data dictionary.
* gitignore file specifies the file to be skipped from uploading to github- the original dataset has 400+ MB.
------
## Acknowledgements
Dataset source https://www.kaggle.com/tunguz/big-five-personality-test/kernels
The personality test was constructed with the "Big-Five Factor Markers" from the IPIP. https://ipip.ori.org/newBigFive5broadKey.htm
