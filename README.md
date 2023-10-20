# Insurance-Claim-Detection
Project 1 assignment where we are looking into a large sample of insurance claims and analyzing common trends amongst fraudulent insurance claims.

## Analysis
Intro:
Fraudulent insurance claims are a massive issue in the United States and make up an estimated 10 to 20 percent of all insurance claims (Bishop 2023). As a result, companies are losing billions in potential profits, forcing the average American citizen to pay an extra 400 to 700 dollars annually (Bishop 2023). When looking closer into the numbers, we realize how big of an issue insurance claims fraud is and we can try looking at statistics to prevent potential fraudulent claims. In this project, our group has meticulously pulled data from online to create a csv file in which we can analyze certain trends within fraudulent claims to see if there are any prevalent correlations. The data we have merged includes all kinds of information about a sample of fraudulent insurance claims which includes data about aspects such as the location, claim amount, amongst other data that might be prevalent to providing us with answers. Using this information, we have generated various plots to justify potential correlations in the data to alert us what features are normally prevalent in false insurance claims.

Analysis of our plots:
Our goal was to answer a variety of questions in regards to fraudulent insurance claims. To begin, we wanted to know what percentage of this sample of flase claims were accepted. To follow up we wanted to analyze specific trends within the false claims (such as if a police report or an injury was present).

We then wanted to see if there was any relationship between the claim amount and the number of claims filed at each amount. Initially, we could assume that most insurance fraud cases deal with smaller amounts. This makes sense as bigger claims would likely be flagged by insurance companies for potential fraud. When creating a scatterplot of the data, our findings support our prediciton as well as shown us what relationship occurs in these cases. We can see that the number of claims exponentially decrease as the claim amount increases. This makes sense because there is a sharp decline in the number of claims that get placed at amounts higher than a few thousand dollars. As we continue to slightly increase the values, the number of claims associated with them severely dip off. As we continue moving further right, the number of claims made seem to taper off as it heads towards 0. As a result, we can assume the relationship between claim amount and number of claims is an exponentially decreasing relationship.

We then wanted to analyze what percentage of the claims were made by specific social classes. We could assume that there is likely correlation between social class versus false claims and the data supports this hypothesis. Middle class people seem to be the biggest offenders of insurance claims fraud, making up nearly half of the claims, while lower and upper class only make up about 1/4th each. When diving deeper into the numbers, we realize that these findings make a lot of sense. The reason we can expect people who are middle class to make up about half of these false claims can be due to several factors. To start, they tend to have a higher intelligence level and more resources readily available to make these claims as opposed to the lower class people. Knowing that the middle class has more resources than the lower class, we can assume they are more aware of certain loopholes and are more apt to successfully get away with fraud than the lower class. When looking at upper class however, we can see that they only make up 1/4th of the claims. We can assume that although they likely have more resources/better education than the middle class, since they have so much money readily available, they may assume it's not worth it to commit insurance fraud of such minor values. The upper class is well off, so committing fraud may be less worth it to them as opposed to someone who has less money.

Closing Statements:


## Citations

- Used [map()](https://www.w3schools.com/python/ref_func_map.asp) function found online to convert integer list to string. This allows us to label bar plot with proper x-ticks:
https://www.w3schools.com/python/ref_func_map.asp

- used [plt.text(ha = 'center')](https://matplotlib.org/stable/users/explain/text/text_props.html) to center value count above the bar plot:
https://matplotlib.org/stable/users/explain/text/text_props.html

- Kaggle dataset used to create merged csv file:
https://www.kaggle.com/datasets/mastmustu/insurance-claims-fraud-data?select=insurance_data.csv

- Insurance Fraud Reference: https://www.iii.org/article/background-on-insurance-fraud

- Plotting multiple bar charts at once: https://www.geeksforgeeks.org/plotting-multiple-bar-charts-using-matplotlib-in-python/

- Insurance Fraud Statistics by Lindsay Bishop: https://www.valuepenguin.com/auto-home-insurance-fraud#fraud
