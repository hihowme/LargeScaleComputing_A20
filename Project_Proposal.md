# MACS 30123 Final Project: Content Recommendation System Based on News
Haihao's proposal for the MACS 30123 final project. 


## Social Science Research Question
How to achieve information achie


## Packaged used expected
`sagemaker` \
`boto3`\
`numpy` \
`pandas` \
`matplotlib`\
`sklearn`\
`seaborn`




## Dataset
[The Multilingual Amazon Reviews Corpus](https://registry.opendata.aws/amazon-reviews-ml/#usageexamples)


## Description
Online customer review plays an important role in consumer's decision making process in 
travelling(TripAdvisor), online shopping(Amazon), and restaurant service(Yelp). Figuring out the review contents
in different languages is essential for the business research to understand the preference heterogeneity across
countries and is also helpful for the companies like Amazon to make targeting strategies.

I would use a novel large scale corpus [The Multilingual Amazon Reviews Corpus](https://registry.opendata.aws/amazon-reviews-ml/#usageexamples) 
to answer this question. The corpus contains reviews in English, Japanese, German, French, Spanish, and Chinese collected between 2015 and 2019.
For each language, there are 200,000, 5,000 and 5,000 reviews in the training, development and test sets respectively.
Applying the cloud computing and machine learning model enabled by AWS `sagemaker` on the dataset, I hope to answer the question




[The Multilingual Amazon Reviews Corpus](https://arxiv.org/abs/2010.02573) by Phillip Keung, Yichao Lu, György Szarvas, Noah A. Smith 