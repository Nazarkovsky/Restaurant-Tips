# Restaurant-Tips

## Abstract
The project was prepared and submitted by C. Pinheiro, E. Carvalho, M. Nazarkovsky, G. Piovesan, I. Barros within the Brazilian "Bootcamp Data Science na prática" by Neuron (https://www.facebook.com/neuronDSAI/photos/a.1924971354499031/2664668797195946/?type=3&amp;eid=ARCBaznRnMGbE-iFheLbf7HyZpHcxpz7vT-F8J9Yl9_BrqHtwnjLsmdbyaE4l4nbEJKXWdg2aLyGuj7B&amp;ifg=1). 

See also here: https://user-images.githubusercontent.com/63872579/107982816-76e4f180-6fa3-11eb-9ce9-e1abadab44ec.png

The project file is uploaded in this repository as PDF

The dataset was provided by the Bootcamp administration as a tips.xlsx 

## Data types
Continious data: Total bill, Size of group, Tip 
Nominal (categorical) data: Sex, Smoker (Smoker/Non-smoker), Week's day, Time (Lunch/Dinner)

## Objectives
The project is devoted to the analysis of factors (regressors) which may affect the tips. As a result, the objective is to determine the conditions for the restaurant for a promotion and/or happy hours  

## Methods and Approaches
● Means Comparison (Tukey-Kramer)
● ANOVA
● Welch’s Method
● Equality of Variances tests.

## Results and Discussions
1. No statistically significant difference has been found in Tip variances by the following factors: Sex, Smoker, Time e Days. But some observations for Time and Days are claimed;
2. There is a positive correlation between Tips, Total_bill and Size of the Group;
3. The biggest contribution to Tips and Total bill is made by group of 2 clients in the dinner time;
4. In terms of the week's days, the biggest contribution to Tips and Total bill is made by a groups of 2 clients, whose percentage is lowered on Sat and Sun;
5. Since Tips and Size of the Group are the lowest on Fri, it would be reasonable to make promotions this day for the groups of 5 or more persons (colleagues, classmates friends, happy hour, birthday parties).
6. More specifically: the promotions for the lunch time on Fri with the focus on the groups of 5 or more persons will improve the run of the restarant's business 
