# UX_product_analysis
A/B testing: A step-by-step guide in Python
In this notebook, we'll go over the process of analyzing an A/B test, from formulating a hypothesis,testing it, and finally interpreting results. For our data, we'll use a (https://www.kaggle.com/zhangluyuan/ab-testing?select=ab_data.csv) dataset from Kaggle which contains the results of an A/B test on what seems to be 2 different designs of a website page (old_page vs. new_page). Here's what we'll do:

1. Designing our experiment
2. Collecting and preparing the data
3. Visualizing the results
4. Testing the hypothesis
5. Drawing conclusions

The UX designer worked really hard on a new version of the product page, with the hope that it would lead to a higher conversion rate. The product manager (PM) instructed that the current conversion rate is about 13% on average throughout the year and that the team would be happy with an increase of 2%, meaning that the new design will be considered a success if it raises the conversion rate to 15%.

Before rolling out the change, the team would be more comfortable testing it on a small number of users to see how it performs, so I suggest running an A/B test on a subset of our user base users.