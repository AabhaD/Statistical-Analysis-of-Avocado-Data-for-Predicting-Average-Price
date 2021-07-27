# Project 1 - Statistical Analysis of Avocado Pricing Dataset for Predicting Average Price.
Purpose and Business Impact of Analysis
• Avocado – One of the most lucrative fruit!
• The main purpose is to understand the pricing trends and factors affecting the average price of 
organic and conventional avocados.
• Understanding the impact of each variable on the pricing model can help businesses better 
predict future pricing and analyze the demand that is generally associated with it.
• Furthermore, businesses will be able to adapt to changes in the avocado sales environment if 
they know what factors are significantly impactful to the demand model. 
• Lastly, this process can help lead to higher profits and lower prices.

Data from - Hass Avocado Board (Focusing on US market only)

Hypothesis Analyzed 
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

Tool used : R

This was a group project.
