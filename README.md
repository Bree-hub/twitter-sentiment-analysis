
# Project Title

Sentiment Classification of Tweets about Apple and Google Products using Natural Language Processing (NLP)by G10 Data Scientists.


## Group Members 

Brenda Kinoti, John Karanja, Victor Mawira, Michelle Mwendwa, Loise Mbago, Stephen Gathai
## Student Pace: Part Time 
## Overview 

This project employs Natural Language Processing (NLP) techniques to perform sentiment analysis on tweets discussing Apple and Google products. The objective is categorizing tweets into positive, negative, or neutral sentiment categories. Our team, G10 Data Scientists, collaborated to preprocess data, conduct exploratory data analysis, engineer features, build models, and evaluate their performance.
## Business Problem 

Understanding public sentiment towards products is pivotal in today's social media-driven landscape. Twitter, as a prominent platform, offers an avenue to analyze and predict sentiment trends. This project employs NLP to create models classifying sentiments in tweets related to Apple and Google products. Crowd Brands and Products Emotions (CBPE), experts in customer sentiment analysis, sought to categorize views expressed in tweets, as well as associate them with specific brands/products. G10 Data Scientists were engaged to construct a sophisticated sentiment analysis prediction system by developing sophisticated NLP models that accurately predict tweet sentiments, aiding CBPE's comprehension of customer perceptions.
## Data Understanding 

The dataset contains 9093 tweets collected from various sources. Each tweet is labeled as 'Positive Sentiment,' 'Negative Sentiment,' 'Neutral,' or 'Cannot Tell.' The tweets discuss Apple, Google, and their products/services

(a)Distribution of Brand /product categories 

![1 Distribution of brand categories](https://github.com/karanja-john/Group10_Phase4/assets/128204573/f76e8354-cffe-4e7f-8f94-d61e097e6b9e)

## Data Preprocessing and EDA

Initial data cleaning involved column renaming and data type conversions. Textual data was tokenized, and stop words were removed. Exploratory Data Analysis included word cloud visualizations, sentiment distribution analysis by product/company, and insights into text length

![2  Top 10 positive tweets](https://github.com/karanja-john/Group10_Phase4/assets/128204573/da368caa-0406-4302-afa5-565d146cde27)

![3  Top 10 Negative tweets](https://github.com/karanja-john/Group10_Phase4/assets/128204573/2bf9f906-dcf1-4cdb-9da9-5129ad745fb0)

![4  Top 10 Neutral tweets](https://github.com/karanja-john/Group10_Phase4/assets/128204573/a1bed042-97cd-4cac-ba03-b0e6bba82f4a)

![5  word cloud of lemmatized tweets ](https://github.com/karanja-john/Group10_Phase4/assets/128204573/1c57236b-12e1-4139-91d4-c1168486fe1b)

## Feature Engineering

Text data underwent tokenization and stop words removal. TF-IDF vectorization transformed text into numerical features.

## Modeling Approach

Baseline Models: We began with Logistic Regression and Naive Bayes as baseline models.
Advanced Models: We explored more advanced models, including Random Forest.
Hyperparameter Tuning: Hyperparameters were fine-tuned using Grid Search.
Addressing Class Imbalance: Oversampling techniques were employed to mitigate class imbalance.


## Model Comparison

Model performance was evaluated based on accuracy, precision, recall, a F1-score and ROC_AUC curves .

![6 Modelling results](https://github.com/karanja-john/Group10_Phase4/assets/128204573/05677cfb-a030-41cd-a972-8d70b4749e17)

Confusion Matrix for random forest
![7 Confusion matrix for  the random forest]
(https://github.com/karanja-john/Group10_Phase4/assets/128204573/c496fbcd-5ef6-4703-b40e-7450d4139eea)

ROC Curve for Random Forest.


![8 ROC  curve for  random forest](https://github.com/karanja-john/Group10_Phase4/assets/128204573/ee4ab796-b96f-4c3a-88d7-768c20b5846f)



## Recommendations:

1.	Brand/Product Awareness:
Observation: The dataset contains numerous mentions of products like the iPad, Apple, and iPad/iPhone apps.

 	Recommendation: Stakeholders and investors should focus on these high-mention products for marketing and investment strategies. The high mention indicates a significant public awareness and interest in these products.
2.	Sentiment Analysis:
Observation: A significant portion of the dataset (60.3%) consists of neutral sentiments, with 33.3% expressing positive emotions and only 6.4% expressing negative emotions.
 	
     Recommendation: These numbers suggest that the overall sentiment towards the discussed brands/products is either positive or neutral. Stakeholders and investors should consider this as a green flag for investing or marketing these products. However, they should also be vigilant about addressing the concerns that lead to negative sentiments to maintain brand reputation.
3.	Frequent Terms:
Observation: The word cloud visualization highlights the most frequently mentioned terms in the dataset.
 	
     Recommendation: Stakeholders should leverage this information for marketing campaigns and product development. Focusing on these terms can help resonate with the target audience. For example, if a particular feature (word) appears frequently, it might be worth emphasizing in marketing materials or considering for further development.
4.	Data-driven Decision Making:
Observation: The dataset has been cleaned, tokenized, and lemmatized, making it a valuable resource for deriving insights.
 	
     Recommendation: Stakeholders should consider further analyses, like trend analysis over time, topic modeling, or deeper sentiment analysis. This can provide more granular insights into customer preferences, pain points, and areas of opportunity.
5.	Engagement Strategy:
Observation: A significant portion of the tweets do not express any emotion towards the brand or product.
 	
     Recommendation: Companies should devise strategies to engage with this neutral audience segment. By converting a neutral customer to a positive advocate, brands can significantly amplify their reach and influence.
6.	Continuous Feedback Loop:
 Observation: The dataset provides real-time feedback from users.
 
     Recommendation: Brands should establish a continuous feedback loop. By actively monitoring social media sentiments, brands can be agile, addressing concerns in real-time, and iterating their products based on real customer feedback.

For potential investors, the primary takeaways are   the general positive sentiment around the products and the high levels of brand/product awareness in the market. Investing in these products or in companies producing these products might be a worthwhile consideration given the current positive sentiment

##  Future Enhancements

Future work involves exploring deep learning models (neural networks) for enhanced sentiment classification, deploying real-time sentiment analysis on social media, and incorporating advanced NLP techniques like word embeddings.
## Conclusion

G10 Data Scientists' collaboration resulted in a successful NLP-based sentiment analysis project. By accurately classifying sentiments in tweets about Apple and Google products, we offer insightful guidance for strategic decisions and customer engagement.
