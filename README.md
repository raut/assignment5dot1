## Will a Customer Accept an In-Vehicle Coupon?

This piece of work represents a submission for an assignment as part of the UC Berkeley Professional Certificate in Machine Learning and Artificial Intelligence. This is a brief investigation into a dataset produced via a survey completed on Amazon's Mechanical Turk, asking participants whether or not they would accept a coupon presented to them in a vehicle whilst driving along. The coupon could be for a café, cheap restaurant, take away restaurant or other categories. The survey respondent has context such as time of day, weather et cetera and basically has to decide if they would accept the coupon or not. This is a relatively well-known dataset hosted [here](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation) at the UC Irvine Machine Learning Repository and used in the paper [A Bayesian Framework for Learning Rule Sets for Interpretable Classification](https://jmlr.org/papers/volume18/16-003/16-003.pdf) by Wang et al, which was published in the Journal of Machine Learning Research.

The Jupyter notebook [here](prompt.ipynb) walks through an investigation into this dataset using the Python Pandas library and providing visualisations through the libraries Matplotlib and Seaborn. The dataset is first explored to look for missing and incomplete data, decisions are made on how to deal with that, then a couple of coupon categories are looked at more closely: bar coupons and take away (take out) coupons.

### Summary of Findings
A summary of the findings from this limited investigation is as follows:
- Most coupons, across all categories, were accepted -- at a rate of approximately 57%
- The most frequently issued coupon was for coffee houses / cafés
- Bar coupons have an acceptance rate that is lower than the overall dataset, at 41%. Based on this limited investigation, respondents who are most likely to accept bar coupons are those who frequent bars four or more times per month and are over the age of 25, or are of any age and don't currently have a child passenger and don't work in fishing, forestry or farming.
- Take away coupons have a high acceptance rate of approximately 74%, which does not vary significantly across age groups, income, frequency of patronage of take away venues, or whether or not the survey respondent / driver is headed towards the business or not.

### Next Steps
If time allowed, curiosity demands a deeper investigation into the take away coupons to see what, if anything, is driving the ~26% decline rate for this category. The accept rate is surprisingly high and seemingly unaffected by the multiple variables examined so far.

