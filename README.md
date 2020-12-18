PREDICTING HOTEL ARRIVALS IN SWITZERLAND WITH GOOGLE TRENDS


Abstract
A 150 word description of the project idea, goals, datasets used. What's the motivation behind your project? How do you propose to extend the analysis from the paper? What story would you like to tell, and why?

The project goal is to show how google trends can improve the predictions of a model initialy based only on features monthly released. The idea is to point out how more recent datasets in time can be useful in better predicting near-future events; especially unusual events such as crisis. In our case, we will be focusing on Tourism in Switzerland. Our goal will be to show how google trends can sharpen our predictions in terms of arrivals at hotels in the country. We will first use official monthly released datas from the Federal Office of Statistics. We will then add Google Trends features to our model and see if these features could lead to a better enticipation of the covid 19 crisis. 

Research Questions

This project must lead to answers to these questions
Which google trends are useful in predicting hotel arrivals in Switzerland ?
Will google trends make more accurate predictions in the context of the COVID-19 crisis than the official statistics of the Switzerland Federal Office of Statistics (which are monthly released)?

Proposed dataset

We chose a dataset offered by the swiss federal statistical office on their website. The name of the dataset is “Hotel accommodation: arrivals and overnight stays of open establishments by year, month, canton and visitors' country of residence” and is available here.

The dataset is already quite clean and the website let us choose a lot of parameters. 

Our main focus is hotel arrivals (instead of hotel nights) since this data is going to be affected more importantly by the COVID crisis. The data is framed from 2010 and is given with a monthly frequency. 


Methods

The methods used are similar to the ones introduced in the paper : “Predicting the Present with Google Trends”. Eventhough, the precise techniques are not explicitly given in the paper, we will apply the following :

1 / Extract and pre-process the data
2/ Correlation estimations on previous months to find the best parameters of our auto-regressive model (order, seasonality..)
3/ Use a rolling window on our auto-regression model (training on the previous months to predict 1 month ahead)
4/ Test the correlation with different Google trends keys (like ‘Hotel’ , ‘Hotel booking’, or ‘Swiss lockdown’) to select which one to use as additional features
5/ Compare models performances with and without Google Trends features 
6/ Conclude


Proposed timeline

First week : each team member will work on his personal part B
Second week : model implementation
Third week : writing the data story (website and video)

Organization within the team

Second week : Implementing the model
Vincent : Clean the dataset
Clément & Antoine : Building up the models and plot the results
Extract and Select the features from Google Trends

Third week : writing a data story
Antoine : writing, video shooting, editing the video
Clément : Setting up a website
Vincent & Xavier : writing the story

Questions for TAs (optional)
Add here any questions you have for us related to the proposed project.

