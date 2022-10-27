# Statistical Analysis of Avocado Pricing Dataset for Predicting Average Price.(Presented on 11/23/2020)

# Executive Summary
Over the last decade, avocados have drawn worldwide popularity and have become household gems. They
have been widely adapted from their use as lotions to their extravagant nutritional value. Due to their
increased adaptation, businesses have widely researched and modeled the avocado market data to further
understand the influential factors that impact their pricing structure. In this report, we have analyzed
market data sourced from the Hass Avocado Board to better understand the features that impact avocado
pricing. We have tested for three hypotheses and modeled various predictive methods to explain what can
be used to predict avocado pricing. The three hypotheses tested are:
1. Avocado Pricing shows more relationship to season rather than region.
2. Over time, across all regions, consumers become less price sensitive.
3. There is a change in avocado prices during the seasonal California wildfires.
The models that are used in this paper include linear regression, subset selection, regularized regression,
and ensemble methods. We utilized the variety of modeling techniques to conclude that the random forest
model ensemble method generates the best predictive performance which lists the type, avocado size, and
bag sizes as the most influential variables in determining average price. Furthermore, our analysis has shown
that there is evidence to support that the season of sales has more of a relationship with average price than
region, pricing demand is inelastic over time, and the relationship of seasonal California wildfires and average
price is significant.

# Data Description - 
Hass Avocado Board (Focusing on US market only)

# Hypothesis Analyzed 
1. Avocado Pricing shows more relationship to season rather than region.
Method Used: Two – Way ANOVA analysis
Conclusion: The comparison of the partial ETA squared values for season (0.045) and region (0.035) display that 
there is evidence of season having a higher effect than region with respect to average price.
2. Over time, across all regions, consumers become less price sensitive.
Method Used: Price Elasticity Analysis over the years
Conclusion: Based on these values of price elasticity, the years of 2015,2016, 2017, 2018, and 2019 all display 
negative values for price elasticity of demand which means that those years were inelastic. We can deny our null 
hypothesis that there is elastic demand as the price changes.
3. There is a change in avocado prices during the seasonal California wildfires.
Method Used: Two-Way ANOVA
Conclusion: Based on low p-value (0.009588 ) the relationship between the independent variables of year and fire 
does seem to be significant with the dependent variable of average price.

# Skills used -
Programming Language - R 
Data Science Skills - Preprocessing, Handling missing values, EDA, Hypothesis Testing, Linear Regression Model, Subset Selection Models, Elastic net, Ensemlbe methods

**This was a group project.
