# FACEBOOK-COMMENT-VOLUME-PREDICTION

## SUMMARY
#### The goal of this project is to predict the number of comments a Facebook post will receive based on characteristics of the page and information about the post. This pursuit is of great potential value because the number of comments on a Facebook post can be used as a proxy for interest in the subject of the page and relevance of the post’s content. Thus this model to predict the number of Facebook comments based on page and post information, can help gain insight into the thoughts and feelings of people active on social media. This, in turn, be used by advertisers, marketers, as well scientists studying social media.

## EDA
#### To begin the exploration, we examine the category of the source of the document e.g. the place, brand, institution etc. There are total 106 categories. The above ﬁgure (ﬁgure 1) shows the count of each category. Thus we can see which category has the most number of pages and in turn the most number of likes. According to the graph below, we can see that the category number 9 has the most count and it happens to be the professional sports team page


## IMPLIMENTING DIFFERENT MODELS 
### Model 1 : Linear Regression
#### Acoording to the r-square value for this model and also according to the graph, this model cannot be considered for prediction. The value is too small.

### Model 2 : Linear Ridge
#### Again, according to the graph and the calculated r-square value, this model cannot be used for prediction.

### Model 3 : Random Forest
#### The r-square value for this model is 0.8961406.
#### Comparing all the models, it can be said that the Random Forest model is the best suited model for this dataset. The test dataset consists of 100 observations i.e 100 posts with diﬀerent features. The goal is to predict the number of comments for these posts will receive. Using the Random Forest Regression model to predict the output variable for the test dataset we get the following

## CONCLUSION
#### The most important ﬁndings of are that the comment volume of a Facebook post can be predicted most accurately by the historical comment volume of the Facebook page and the number of Facebook post shares. It appears that user controllable features such as character length and day of posting have relatively little impactonthecommentvolume, aswewerenotabletoincreasetheaccuracyofthesinglefeaturebaselineby adding those input attributes. The number of posts on that page in the preceding 24 hours and the number of post shares largely predicts the amount of comments a post will receive.

