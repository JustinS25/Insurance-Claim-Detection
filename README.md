# Insurance-Claim-Detection
Project 1 assignment where we are looking into a large sample of insurance claims and analyzing common trends amongst fraudulent insurance claims.

## Analysis
Intro:
Fraudulent insurance claims are a massive issue in the United States and make up an estimated 10 to 20 percent of all insurance claims (Bishop 2023). As a result, companies are losing billions in potential profits, forcing the average American citizen to pay an extra 400 to 700 dollars annually (Bishop 2023). When looking closer into the numbers, we realize how big of an issue insurance claims fraud is and we can try looking at statistics to prevent potential fraudulent claims. In this project, our group has meticulously pulled data from online to create a csv file in which we can analyze certain trends within fraudulent claims to see if there are any prevalent correlations. The data we have merged includes all kinds of information about a sample of fraudulent insurance claims which includes data about aspects such as the location, claim amount, amongst other data that might be prevalent to providing us with answers. Using this information, we have generated various plots to justify potential correlations in the data to alert us what features are normally prevalent in false insurance claims.

Analysis of our plots:
Our goal was to answer a variety of questions in regards to fraudulent insurance claims. To begin, we wanted to know what percentage of this sample of flase claims were accepted. To follow up we wanted to analyze specific trends within the false claims (such as if a police report or an injury was present).

We then wanted to see if there was any relationship between the claim amount and the number of claims filed at each amount. Initially, we could assume that most insurance fraud cases deal with smaller amounts. This makes sense as bigger claims would likely be flagged by insurance companies for potential fraud. When creating a scatterplot of the data, our findings support our prediciton as well as shown us what relationship occurs in these cases. We can see that the number of claims exponentially decrease as the claim amount increases. This makes sense because there is a sharp decline in the number of claims that get placed at amounts higher than a few thousand dollars. As we continue to slightly increase the values, the number of claims associated with them severely dip off. As we continue moving further right, the number of claims made seem to taper off as it heads towards 0. As a result, we can assume the relationship between claim amount and number of claims is an exponentially decreasing relationship.

We then wanted to analyze what percentage of the claims were made by specific social classes. We could assume that there is likely correlation between social class versus false claims and the data supports this hypothesis. Middle class people seem to be the biggest offenders of insurance claims fraud, making up nearly half of the claims, while lower and upper class only make up about 1/4th each. When diving deeper into the numbers, we realize that these findings make a lot of sense. The reason we can expect people who are middle class to make up about half of these false claims can be due to several factors. To start, they tend to have a higher intelligence level and more resources readily available to make these claims as opposed to the lower class people. Knowing that the middle class has more resources than the lower class, we can assume they are more aware of certain loopholes and are more apt to successfully get away with fraud than the lower class. When looking at upper class however, we can see that they only make up 1/4th of the claims. We can assume that although they likely have more resources/better education than the middle class, since they have so much money readily available, they may assume it's not worth it to commit insurance fraud of such minor values. The upper class is well off, so committing fraud may be less worth it to them as opposed to someone who has less money.

Claims analysis keeps insurance companies current on policy claim trends. This type of analysis not only helps review overall performance but it is also instrumental when trying to identify patterns of fraud. Our analysis clearly showed how claim amounts within each insurance category over exceeded the premium amount. Life insurance claims had an average of $54K in payouts with an average premium amount of just $75. This type of analysis can easily help detect a type of insurance fraud called "padding" which is a term used when claims are being inflated resulting in a much higher payout. 

The correlation between premium and claim amount is a fundamental aspect of insurance underwritting and risk management. The correlation was evident in our analysis in the sense that, on average, as premium increased so did claim amounts. This is usually seen with high risk individuals since they are more likely to file claims with higher amounts due to their high premiums, however our analysis showed the opposit. 44% of claims were filed by low risk individuals while 14.6% were filed by high risk individuals. We dug a little deeper into this finding and was able to clearly see the huge gap between premium and claim amounts within each risk segment. The high risk segment filed claims totalling $24M while the low risk segment totalled $73M, a little over 3 times that of the high risk segment. 

* Claims analysis is instrumental when trying to identify patterns of fraud.
* The correlation between premiums and claim amounts is evident in the sense that, on average, as premium amount goes up so does claim amount. 
* Reasons why low risk individuals could be commiting fraud are:
    * Perceived opportunity for the low risk segment
    * Reduced monitoring can create an opportunity for some individuals to attempt fraudulent activities
    * Low risk individuals think they are less likely to be caught because this segment often has a history of low claims and a lower level of monitoring
    * Committing fraud inadvertently through honest mistake or not understanding terms and conditions of coverage
    * High-risk segments are often closely monitored by insurance companies due to their elevated likelihood of filing claims. This increased monitoring can act as a restraint for potential fraudsters, as they are more likely to be detected.

Closing Statements:
Fraudulent insurance claims are a major issue to this day, but there are many trends we can look for to help get ahead of it. To paraphrase from the Insurance Fraud Reference listed below, we can see that people who commit insurance fraud range from "people who are organized criminals, professionals who inflate costs of insurance, or even the average person trying to cover their deductable". Although anyone can commit this fraud, judging from our plots it appears that many cases are made by the middle class and include variables such as injuries and police reports. As a result, there should be safeguards put into place to examine such claims more closely to prevent this fraud from the start. Had there been more extensive screenings of cases which included police reports, we could have potentially seen the number of claims that were accepted, decrease. As a result, people would pay less premiums to make up for such cases of fraud.

## Citations

- Used [map()](https://www.w3schools.com/python/ref_func_map.asp) function found online to convert integer list to string. This allows us to label bar plot with proper x-ticks:
https://www.w3schools.com/python/ref_func_map.asp

- used [plt.text(ha = 'center')](https://matplotlib.org/stable/users/explain/text/text_props.html) to center value count above the bar plot:
https://matplotlib.org/stable/users/explain/text/text_props.html

- Kaggle dataset used to create merged csv file:
https://www.kaggle.com/datasets/mastmustu/insurance-claims-fraud-data?select=insurance_data.csv

- Insurance Fraud Reference (Source: Property Casualty Insurers Association of America; Coalition Against Insurance Fraud): https://www.iii.org/article/background-on-insurance-fraud

- Plotting multiple bar charts at once: https://www.geeksforgeeks.org/plotting-multiple-bar-charts-using-matplotlib-in-python/

- Insurance Fraud Statistics by Lindsay Bishop: https://www.valuepenguin.com/auto-home-insurance-fraud#fraud
