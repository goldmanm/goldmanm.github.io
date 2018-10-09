---
layout: layout-post
title: tweeting about presidents
summary: an experiment in sentiment analysis
source: /app/posts/lab/tweets
preview-img: /app/posts/lab/tweets/preview.jpg
preview-css: post-preview-std post__imgPreview--dark
category : lab
tags : [machine_learning, politics]
published : true
type : blog
---

As November 2016 came to an end and the news about Hillary's emails and Donald's derogatory recordings quieted, I thought it'd be interesting to see how much hate was being directed at each of them. Using a database of hate speech, I used neural nets and classification trees to see which tweets which discussed the president and former presidential candidate would be classified as hate speech.

#### Executive summary

Modelling of politics has become increasingly common since mid-2000s. This has increasingly involved
understanding people’s emotions in more time-sensitive manner than done by traditional polling metrics.
Sentiment analysis can be used to get this information. This project aims to analyze possibilities in this
lucrative space. In this analysis, we take 15,000 tweets labeled as hate speech or offensive, process the
text with standard tokenization techniques. After dividing the data into validation, training, and test,
we analyze it with neural network, naive Bayes and decision trees. We used validation to determine
the optimum nodes, variables and tree depth for each case respectively. The misclassification error in
the test data, through cross validation, was 25.0±0.9% for naive Bayes, 23.1±0.6 for decision tree, and 24.2±0.8%. From this, the best model was determined to be decision tree.

To try out the data on politically relevant data, Twitter API was utilized to obtain 27,000 tweets
containing comments about Hillary Clinton, Donald Trump, and birthdays (as a control). The best
performing model was applied to classify the tweets. Hate speech with Trump in it had the highest
frequency, over five times the hate speech rate of the ‘birthday’ control. Many of these hate messages
appeared from critics of the President Elect’s cabinet choices. The highest frequency of offensive
messages occurred for the ‘birthday’ category, which may indicate an issue with the model recognizing
friendly messages that contain language that may offend some people.

You can read the full report [here]({{ page.source}}/report.pdf).
