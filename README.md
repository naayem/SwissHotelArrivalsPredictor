# Quality of food offered in North America and Western Europe

# Abstract
We would like to uncover insights about the nutritional quality of food. Food habits vary among countries, we would like to point out which areas offer the least healthy options by observing the products offered there.

Differences in quality could be explained by cultural habits, economic situation and also legislations. Additives restrictions in particular would be a good example of these differences in regulations. Indeed, some artificial dyes are legal in the US but not in Europe. We would like to uncover how common these products are in countries where these dyes are legal. Can we see that banning an ingredient in a certain country reduces its presence in other places?

We will also consider the amounts of sugar and fat in different products, and see how widespread ingredients like palm oil are for example.

We will use the Open Food Facts database which will allow us to get access to ingredients, allergens, additives and all the other information available on food labels.

# Research questions
There are a lot of questions to answer. Here are a few examples of topics and correlated questions:

General questions
* Where is food with the most additives sold?
* What is the proportion of palm oil or ingredients derived palm oil in products with a high quantity of fat or sugar?
* What are the most common ingredients per region?

Sugar, fat
* Where are the most sugary / fat products sold?
* Where are they produced?
* How many products combines sugar and fat?
* Where do they mostly come from? Where are they sold?
* What are the main companies who sell them?

Dangerous ingredients
* Are some dangerous additives forbidden in some countries widely available in others?

Legislation
* What is the maximal value of sugar content (or fat content, or other metrics) for each country?
* Can we identify federal or continental restrictions?
* What are the most / least restrictive places?

# Dataset
We plan to use the Open Food Facts database. It is a TSV file with fields concerning both the metadata of the product (its origin, where it is available, the brand that sells it, ...)  and extensive nutritional data. All the fields available are indicated here.

The size of the dataset is 1.6 GB, which is sufficiently small to load it entirely in memory.


The dataset mostly contains products from Western Europe and North America. We will thus focus our research on those areas. Products from Asia, Africa or South America are too poorly referenced in the dataset to get relevant informations.

# Contributions
- Louis: Cleaning for milestone 2 and readme for first 2 milestones. Additives story
- Aurélien: Sugar story in final, data analysis for last milestone.
- Kyle: Palm oil story, plotting graphs and maps, setting up website and domain name.
