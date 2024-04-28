The dataset was retrieved from Kaggle by Amir Motefaker (2023): https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset

A/B Testing and its meaning in (product) data analysis:

Objectives of marketing campaign analysis are to support businssses understand how well the ads are working and how to optimise them. For this, A/B Testing is used in practice. This test is meaningful to understand e.g. users' product satisfaction, user engagement, etc. A/B Testing consists of randomised experiments, meaning two variants (A and B) are tested against each other. This includes statistical hypothesis testing (in the field of Statistics it is called "Independent samples t-test), to test which variant is working better. Goals of A/B Testing can be to boost sales, having a higher reach, approach new customers, etc. 

The objective of this analysis is to evaluate the effectiveness of a marketing campaign by comparing two distinct groups: the "Test Campaign" (experimental) group and the "Control Campaign" (control) group. Using an A/B testing framework, it will assess if the test campaign outperforms the control campaign. Differences in independent variables between the two groups are analysed, seeking to identify areas of improvement and inform future marketing strategies.

Dataset Description:

The dataset comprises data collected during a marketing campaign, consisting of observations from two distinct groups: the test campaign and the control campaign. Each observation includes information on various independent variables related to campaign performance, such as advertising spend, impressions, reach, website interactions, searches, and conversion metrics.

Campaign Groups:

- Test Campaign: The group exposed to the modified or experimental version of the marketing campaign.
- Control Campaign: The group exposed to the standard or existing version of the marketing campaign, serving as a baseline for comparison.

Independent Variables:
- Spend [USD]: The amount of money spent on advertising for each campaign group.
- Impressions: The number of times the campaign content was displayed to users.
- Reach: The total audience reached by the campaign.
- Website Clicks: The number of clicks received on the campaign's website link.
- Searches: The number of searches or queries related to the campaign or product.
- View Content: The number of times the campaign content was viewed or interacted with.
- Add to Cart: The number of times the product was added to the shopping cart.
- Purchase: The number of completed purchases or conversions resulting from the campaign.

Analysis Approach:
Using statistical techniques such as exploratory data analysis hypothesis testing as well as KPI metric testing of independent variables between the test and control campaign groups were checked. By assessing differences in performance metrics, insights into the effectiveness of the test campaign relative to the control campaign and identify areas for optimisation in future marketing efforts are drawn.

The analysis suggests that the Control Campaign generated higher sales and user engagement overall. It attracted more product views and resulted in more products added to the cart, leading to higher sales.

On the other hand, the Test Campaign had a higher conversion rate for products added to the cart. This means that although it had fewer product views, a higher percentage of those views resulted in actual purchases.

In conclusion, the Test Campaign is suitable for targeting specific products to a targeted audience, whereas the Control Campaign is more effective for marketing multiple products to a broader audience.
