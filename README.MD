# 5 Personality Test- analysis of the results for European countries

The aim of this analysis is to evaluate the trends in human personalities across different European countries.
Initial work focuses on cleaning the data, dimensionality reduction and identifying the aggregated trends. 
Any additional contributions will be appreciated.

## Medium post
https://medium.com/@jakubgajdul/4-things-that-data-tells-us-about-our-personalities-210cdd8f71f

## Summary of the analysis

**1. What traits are common for personalities across Europe?**
* The average for all characteristics is near 3 on the 1 to 5 scale.
* Highest variability measured by the standard deviation observed in emotional stability (σ=0.65).
* Openness scored on average higher than other personality traits (μ=3.31).

**2. Is there a link between different personality traits?**

The strongest correlation identified for 
* openness and consciousness: 0.33
* agreeableness and extraversion: 0.32
* Correlation between emotional stability and extraversion significantly lower: 0.063.

**3. Can UK citizens personality explain the unorthodox government response to COVID-19? (compare the results to Poland)**
* Survey responses suggest that, on average, British respondents score 0.07 higher on extraversion, 0.05 less on emotional stability and 0.05 lower on conscientiousness. 
* These traits could explain some of the asymmetric government responses between the two countries.

**4.Can we predict respondents nationality based on their personality traits?**
* The xgboost model scored 13.2% better than a random guess.

------
## Libraries used:
* pandas
* matplotlib
* seaborn
* numpy
* collections (defaultdicst)
* xgboost
* sklearn
------
## Files in the repository:
* personality_analysis.ipynb is the Jupyter notebook with the analysis
* codebook.txt file explains the dataset source as well as data dictionary.
* gitignore file specifies the file to be skipped from uploading to github- the original dataset has 400+ MB.
------
## Acknowledgements
* Dataset source https://www.kaggle.com/tunguz/big-five-personality-test/kernels

* The personality test was constructed with the "Big-Five Factor Markers" from the IPIP. https://ipip.ori.org/newBigFive5broadKey.htm
