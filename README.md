# Neural_Network_Charity_Analysis
## Overview
 This analysis was performed in order to determine which charities would have the most success if they were given a donation from alphabet soup.

## Results
### Data Preprocessing
The target variable in this analysis is simply titled 'IS_SUCCESSFUL'. The remaining features are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT. The features that were dropped from the data frame were 'NAME' and 'EIN'.
![alt text](http://url/to/features.png)  

### Compiling, Training, Evaluating the model
I chose to include 10 hidden layers with neurons ranging from 27 to 12 I chose the relu activation function because it seemed to work best. However I was not able to achieve target performance level. I reduced the number of bins to achieve a higher level of performance which had a positive effect.

## Summary
 the new network model did a fair job at trying to make connections between the data set however I believe a higher accuracy score could be derived from a supervised learning algorithm. I would recommend a naïve random on your sampling supervised ML algorithm because this date is it may benefit from having the under sampling capability.