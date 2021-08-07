# [Analysis of the relationship between diet and Covid-19 death rates - General EDA - Project Overview:](https://t-ded.github.io/t-ded-portfolio/projects/covid-diet/)

## Project Summary

- **Comprehensive data exploration and visualization** including **geographical analysis**, which is something the author has never worked with before
- This project may **throw light on some of the most common misconceptions** regarding diet as well as Covid-19 death rates, helping in fights against hoaxes and fake news
- The analysis presented also enables us to compare some of the countries as well as continents and **find some important patterns** in terms of Covid-19 deaths, obesity and undernourishment
- Particular focus is given to **the Czech Republic** along with Europe, especially Central Europe
- No ML algorithm has been implemented due to the features showing very little relation (it would be extremely hard to make a model perform at least at a basic level) as well as the number of samples (countries) being very low

## Project Background

- The dataset has been chosen for some of its practical usecase as well as for the significance of the topic in the current world
- The [initial dataset](https://www.kaggle.com/mariaren/covid19-healthy-diet-dataset) contains information about 170 countries in more than 25 food type columns
- We have decided to only revolve this analysis around EDA and geographical analysis for the purpose of learning the concept

## Project outline
      
- State the initial hypotheses and assumptions, decide for an approach 
- Make necessary imports, take first look at the dataset
- Decide how to clean the dataset and engineer some of the missing values
- Analyse the individual distribution of some of the important features
- Research the relations of undernourishment, obesity and deaths
- Perform an analysis of diet and deaths & obesity relations
  - Try splitting food into generally healthy & unhealthy
  - Give some additional focus to vegan lifestyle
- Initiate geographical analysis
  - Start out with general world analysis
  - Pay special attention to Europe
  - Split the dataset into continents and compare these (add Czechia, Slovakia & Central Europe)
- Correlation inspection

## Hypotheses and notes

- Some food products will lead to higher death percentages - alcohol, animal fats, sugars, stimulants
- Animal fats and sugars will also lead to higher obesity percentage
- On the contrary, food such as fish, fruits or vegetables will be correlated with lower death rates
- Since obesity is a risk factor of covid, obesity & deaths will be positively correlated
- Undernourished percentage and death rate will also be positively correlated since there are higher percentages of undernourishment in developing countries with worse health care
        
## Hypotheses after examination

- Animal fats and sugars show slight positive impact on the Covid-19 death rates, this is also true for cereals
- Alcohol and stimulants, as well as spices, show the exact opposite relation - we have concluded that this is due to these products being more consumed in well-developed countries
- In general, sugar and most of the animal products (eggs, milk, meat, fats etc.) show clear signs of positive relation with obesity percentages
- Fish & seafood seem to battle covid-19 death rates quite effectively, however, this is not true for other generally healthy food such as fruits or vegetables
- Obesity and deaths seem to have no relationship whatsoever
- Undernourishment and death percentage have quite strong positive correlation

## Possible next steps

- Transform the variables, find our impactful features and try to re-build some ML models
- Obtain additional information about the countries, such as health care quality etc. in order to find some deeper patterns
- Consult the features with a nutrition specialist and work together towards a relevant research
- Note: This analysis would be far more effective overall if we managed to obtain data about some individual samples from the countries (e.g. 100 people from the general population for each country) and not only the average percentages
