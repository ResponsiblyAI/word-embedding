SemEval-2018 Task 1 Affect in Tweets Dataset
Feb 2018
Copyright (C) 2018 National Research Council Canada (NRC)
----------------------------------------------------------------


Contact: Saif Mohammad (saif.mohammad@nrc-cnrc.gc.ca)


Terms of Use: 
-------------------------------------------------

1. If you use this dataset, cite the paper below:

Saif M. Mohammad, Felipe Bravo-Marquez, Mohammad Salameh, and Svetlana Kiritchenko. 2018. Semeval-2018 Task 1: Affect in tweets. In Proceedings of International Workshop on Semantic Evaluation (SemEval-2018), New Orleans, LA, USA, June 2018.

@InProceedings{SemEval2018Task1,
 author = {Mohammad, Saif M. and Bravo-Marquez, Felipe and Salameh, Mohammad and Kiritchenko, Svetlana},
 title = {SemEval-2018 {T}ask 1: {A}ffect in Tweets},
 booktitle = {Proceedings of International Workshop on Semantic Evaluation (SemEval-2018)},
 address = {New Orleans, LA, USA},
 year = {2018}}

2. Do not redistribute the data. Direct interested parties to this page: https://competitions.codalab.org/competitions/17751.

3. National Research Council Canada (NRC) disclaims any responsibility for the use of the dataset and does not provide technical support. However, the contact listed above will be happy to respond to queries and clarifications.



Tasks: 
-------------------------------------------------
The SemEval-2018 Task 1 shared task included an array of sub-tasks where systems had to automatically determine the intensity of emotions (E) and intensity of sentiment (aka valence V) of the tweeters from their tweets. (The term tweeter refers to the person who has posted the tweet.) A multi-label emotion classification task for tweets was also included. For each task, separate training, development, and test datasets for English, Arabic, and Spanish tweets were provided. 

1. EI-reg (an emotion intensity regression task): Given a tweet and an emotion E, determine the intensity of E that best represents the mental state of the tweeter — a real-valued score between 0 (least E) and 1 (most E).
Separate datasets are provided for anger, fear, joy, and sadness.

2. EI-oc (an emotion intensity ordinal classification task): Given a tweet and an emotion E, classify the tweet into one of four ordinal classes of intensity of E that best represents the mental state of the tweeter.
Separate datasets are provided for anger, fear, joy, and sadness.

The classes:
0: no E can be inferred
1: low amount of E can be inferred
2: moderate amount of E can be inferred
3: high amount of E can be inferred

3. V-reg (a sentiment intensity regression task): Given a tweet, determine the intensity of sentiment or valence (V) that best represents the mental state of the tweeter — a real-valued score between 0 (most negative) and 1 (most positive).

4. V-oc (a sentiment analysis, ordinal classification, task): Given a tweet, classify it into one of seven ordinal classes, corresponding to various levels of positive and negative sentiment intensity, that best represents the mental state of the tweeter.

The classes:
3: very positive mental state can be inferred
2: moderately positive mental state can be inferred
1: slightly positive mental state can be inferred
0: neutral or mixed mental state can be inferred
-1: slightly negative mental state can be inferred
-2: moderately negative mental state can be inferred
-3: very negative mental state can be inferred

5. E-c (an emotion classification task): Given a tweet, classify it as 'neutral or no emotion' or as one, or more, of eleven given emotions that best represent the mental state of the tweeter.

The emotional classes:
anger (also includes annoyance and rage) can be inferred
anticipation (also includes interest and vigilance) can be inferred
disgust (also includes disinterest, dislike and loathing) can be inferred
fear (also includes apprehension, anxiety, concern, and terror) can be inferred
joy (also includes serenity and ecstasy) can be inferred
love (also includes affection) can be inferred
optimism (also includes hopefulness and confidence) can be inferred
pessimism (also includes cynicism and lack of confidence) can be inferred
sadness (also includes pensiveness and grief) can be inferred
suprise (also includes distraction and amazement) can be inferred
trust (also includes acceptance, liking, and admiration) can be inferred

Here, E refers to emotion, EI refers to emotion intensity, V refers to valence or sentiment intensity, reg refers to regression, oc refers to ordinal classification, c refers to classification. 


NOTE:
The official test datasets for the EI-reg and V-reg English tasks had two parts:
1. The Tweet Test Set: tweets annotated for emotion/valence intensity (similar to the training and development sets);
2. The Mystery Test Set: automatically generated sentences to test for unethical biases in NLP systems (with no emotion/valence annotations).
 
The official evaluation metrics reported on the Leaderboard were calculated only on the Tweet Test Set. The Mystery Test Set was not used by the official evaluation script to calculate the official evaluation metrics. The Mystery Test Set is not included into this distribution. For more information about the bias evaluation, see the paper below:

Kiritchenko, S. and Mohammad, S. (2018). Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems. Proceedings of the 7th Joint Conference on Lexical and Computational Semantics (*SEM), New Orleans, USA, 2018.




************************************************
More Information
************************************************

Saif M. Mohammad, Felipe Bravo-Marquez, Mohammad Salameh, and Svetlana Kiritchenko. 2018. Semeval-2018 Task 1: Affect in tweets. In Proceedings of International Workshop on Semantic Evaluation (SemEval-2018), New Orleans, LA, USA, June 2018.

The paper below describes how the data was created:

Saif M. Mohammad and Svetlana Kiritchenko. Understanding Emotions: A Dataset of Tweets to Study Interactions between Affect Categories. In Proceedings of the 11th Edition of the Language Resources and Evaluation Conference (LREC-2018), May 2018, Miyazaki, Japan.


************************************************
CONTACT INFORMATION
************************************************
Saif M. Mohammad
Senior Research Officer, National Research Council Canada
email: saif.mohammad@nrc-cnrc.gc.ca
phone: +1-613-993-0620
