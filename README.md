# yelp_review

This is our exploratory journey of yelp dataset. The main topic is about reviews' topic modeling. 

Our team has Yi Zhu, Yili Yu, Boyang Wei, Lin Xu and Xiangke Chen, Yusha Wang

This project focuses on goal A. We will perform text analytics on the yelp dataset to derive business insights from customers’ restaurant reviews. We hope to provide restaurant owners with a timely review summary. Our goal is to help business owners identify issues that they might not be aware of and serve their customers better. Our target audience will be restaurant owners and managers. The dataset comes from https://www.yelp.com/dataset.

We hope to build a review Dashboard for restaurant owners/managers containing review score trends, review keywords, negative review analysis (if negative review detected), etc. 

**Analysis approach**

- Sentence-level: Quantifying the polarity scores of the comments by extracting keywords (‘too salty’, ‘poor service’, ‘rats in the kitchen’, etc) from reviews with negative feedback to help restaurants understand the reasons behind and improve. 

- customer-level: classify the opinion of each review into a positive, negative or neutral sentiment by deciphering the sentiment tendency for each review and evaluating how satisfied or dissatisfied customer is based on the total score.

- Entity and Aspect level: analyze how a word, especially negative keyword, contributes to the overall score for restaurant, then summarize sentiment analysis and negative review reason analysis and display on restaurant dashboard (for restaurant managers to view) on a regular basis.

We plan to use the following tools : SparkML, Tableau, Databrick, AWS

We also publish our dashboard in *Tableau Public*, click the [link](https://public.tableau.com/profile/xiangke.chen#!/vizhome/YelpReviewAnalysis_15758570841320/final) and watch.

![Qw9xi9.png](https://s2.ax1x.com/2019/12/09/Qw9xi9.png)
