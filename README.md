# Insurance-Claim-Detection
Project 1 assignment where we are looking into a large sample of insurance claims and seeing how insurance fraud is detected.

## Premium vs Claims Amount Analysis
Claims analysis keeps insurance companies current on policy claim trends. This type of analysis not only helps review overall performance but it is also instrumental when trying to identify patterns of fraud. Our analysis clearly showed how claim amounts within each insurance category over exceeded the premium amount. Life insurance claims had an average of $54K in payouts with an average premium amount of just $75. This type of analysis can easily help detect a type of insurance fraud called "padding" which is a term used when claims are being inflated resulting in a much higher payout. 

The correlation between premium and claim amount is a fundamental aspect of insurance underwritting and risk management. The correlation was evident in our analysis in the sense that, on average, as premium increased so did claim amounts. This is usually seen with high risk individuals since they are more likely to file claims with higher amounts due to their high premiums, however our analysis showed the opposit. 44% of claims were filed by low risk individuals while 14.6% were filed by high risk individuals. We dug a little deeper into this finding and was able to clearly see the huge gap between premium and claim amounts within each risk segment. The high risk segment filed claims totalling $24M while the low risk segment totalled $73M, a little over 3 times that of the high risk segment. 

## Conclusions
* Claims analysis is instrumental when trying to identify patterns of fraud.
* The correlation between premiums and claim amounts is evident in the sense that, on average, as premium amount goes up so does claim amount. 
* Reasons why low risk individuals could be commiting fraud are:
    * Perceived opportunity for the low risk segment
    * Reduced monitoring can create an opportunity for some individuals to attempt fraudulent activities
    * Low risk individuals think they are less likely to be caught because this segment often has a history of low claims and a lower level of monitoring
    * Committing fraud inadvertently through honest mistake or not understanding terms and conditions of coverage
    * High-risk segments are often closely monitored by insurance companies due to their elevated likelihood of filing claims. This increased monitoring can act as a restraint for potential fraudsters, as they are more likely to be detected.

## Citations

- Used map() function found online to convert integer list to string. This allows us to label bar plot with proper x-ticks.