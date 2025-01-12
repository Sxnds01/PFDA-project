# Project: Investigating Alcohol Consumption Trends in Ireland

## Objective
The main objective of this project is to analyse how the consumption of alcohol has changed over the last few years. This is light of the Public Health (Alcohol) Act being passed in 2018. This Act contained measures such as restrictions on alcohol advertising, minimum unit pricing and health warning labels in order to lower the amount of alcohol consumed to about 9.1 litres per person. The amount consumed per person on average was recoreded 11.3 litres in 2016. This project takes a look at recent data sets to discuss whether the measures put in place so far have had an effect.

## The Data
The two data sets used contain the consumption and binge drinking habits of people aged 15 years and older. The consumption percentage data set contains the country of birth of the respondents while the binge drinking data sets contain the age ranges of the respondents. Alcohol consumption dataset can be found at: https://data.gov.ie/dataset/his46-alcohol-consumption-in-last-12-months
The binge drinking data set can be found at: https://data.gov.ie/en_GB/dataset/his47-binge-drinking

## Graphs
The csv files were read using `pandas` and the graphs were plotted using `seaborn` and `matplotlib`. Columns that didn't contain information that was needed were dropped using `df.drop`. The data also had to be filtered to the rows that had either 'all countries' or 'all ages' as these rows had all the averages and plotting this row along with the other rows of data would give inaccurate percentages.

## Discussion
The main conclusion is that it is unclear whether or not the measures brought have made much of a difference to the drinking habits of the Irish population. The rise and fall appear to be due to factors outside of people's control such as Covid. And as alcohol consumption is slowly on the rise again only time will tell if the measures taken will have any effect, particularly the warning labels in 2026.

## References
1. https://www.who.int/data/gho/data/themes/global-information-system-on-alcohol-and-health
2. https://iris.who.int/bitstream/handle/10665/274603/9789241565639-eng.pdf
3. https://www.drugsandalcohol.ie/34737/
4. https://alcoholireland.ie/facts-about-alcohol/how-much-do-we-drink/
5. https://bmjopen.bmj.com/content/8/5/e021932#ref-2
6. https://www.drugsandalcohol.ie/40656/1/Drugnet_Ireland_issue_87.pdf
7. https://www.drugsandalcohol.ie/34737/
8. https://www.drinkaware.ie/research-reveals-men-are-more-likely-to-binge-drink-than-women-with-men-more-prone-to-drinking-alone-at-home/
9. Dataset for alcohol consumption in the last 12 months: https://data.gov.ie/dataset/his46-alcohol-consumption-in-last-12-months
10. Dataset on binge drinking: https://data.gov.ie/en_GB/dataset/his47-binge-drinking
11. Discussion info: https://www.drugsandalcohol.ie/37618/1/AAI-PHAA-Progress-Review-11.22.pdf
12. Discussion info: https://www.drugsandalcohol.ie/40656/1/Drugnet_Ireland_issue_87.
