# 5 Personality Test- analysis of the results for European countries

The aim of this analysis is to evaluate the trends in human personalities across different European countries.
Initial work focuses on cleaning the data, dimensionality reduction and identifying the aggregated trends. 
Feedback and contributions will be appreciated.

## Medium post
https://medium.com/@jakubgajdul/4-things-that-data-tells-us-about-our-personalities-210cdd8f71f

## Summary of the analysis

**1. Is there any trend in personalities across European countries? scale: -2 to 2**
* The average for most of the characteristics near 0 (neutral).
* The average agreeableness (μ=0.66) and openness (μ=1) slightly higher than for other traits.
* Highest variability measured by the standard deviation observed in extraversion (σ=0.92).

**2. Is there a link between different personality traits?**
* The strongest correlation identified for extraversion and agreeableness: 0.3.
* There are no significant correlations to point out between different personality traits.

**3. Can UK citizens personality explain the delayed government response to COVID-19? Base on the comparison of Polish versus British responses.**
* British respondents also score 0.23 on extraversion, implying that they may find it harder to refrain from socialising. 
* Other traits did not differ enough to make any conclusions.

**4.Can we predict respondents nationality based on their personality traits?**
* The xgboost model scored 13% better than a random guess.

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
