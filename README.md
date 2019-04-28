## Exploratoty data analysis on white wine quality with R 
Using R and Rstudio, I conducted data analysis on white wine quality data to find out which chemical properties influence the quality of the wine.

## Description
This data set contains 4,898 white wines with 11 variables on quantifying the chemical properties of each wine.
At least 3 wine experts rated the quality of each wine, providing a rating between 0 (very bad) and 10 (very excellent).
We will explore to find out which chemical properties influence the quality of white wines. 
Also we will explore the relation within the chemical properties.

## Conclusion & Insights 
This data set contains information on 4898 white wines across 11 input attributes and 1 output attribute(quality).
We investigated the correlation between quality and input variables and between input variables.
There was a relatively strong relation between quality and alcohol, density, chlorides.
In other words, better quality white wines tend to have higher alcohol percentage, lower density and lower chlorides.
Also, alcohol and density has a liner relation, assumably it is because the density of ethanol is lower than water.

We have to be aware of that there are some limitations in this analysis:
First, We have limited samples. Especially the sample number of quality 3 and 9 is very small. To get more accurate insights from these dataset, we would need to collect more data for these qualities.
Second, there is no other information that could influence the quality such as grape types, wine brand, wine selling price, etc, due to privacy and logistic issues.
