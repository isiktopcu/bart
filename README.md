# Tweet Classification with BART Large MNLI 
Narrative and sentiment classification of UK tweets scraped using the word 'immigrant'(November 2021 - July 2021) 
and the correlation between the economic variables such as consumer price index(CPI),Consumer Prices Index including owner occupiers' housing costs (CPIH),
owner occupiers' housing costs (OOH) and seasonally adjusted total unemployment rate(UR). 
****
**Contains:**
1. UK dataset scraped using the tweepy module.   
2. Narrative classification using BART Large MNLI Model using the labels: Economy, Politics, Human Trafficking, Citizenship, Border Crossing,
Illegal Migrants and Human Rights, which have been intuitively decided by running multiple GSDMM models on the data. 
3. Sentiment analysis using BART Large MNLI Model using the labels: Anti-Immigrant Sentiment or Pro-Immigrant Sentiment. 
4. Daily overall sentiment score by multiplying the negative sentiment scores by zero and getting a daily sentiment mean. 
5. Daily average sentiment score for each narrative by grouping every narrative and applying the same method as above. 
6. Performing pairwise correlation between the 'Economy' daily average sentiment score and the economic variables. 

Does not contain the dataset for ethical purposes. 
****