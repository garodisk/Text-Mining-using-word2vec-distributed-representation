# Text-Mining-using-word2vec-distributed-representation

UMICH SI650 - Sentiment Classification

This is a text classification task - sentiment classification. Every document (a line in the data file) is a sentence extracted from social media (blogs). Your goal is to classify the sentiment of each sentence into "positive" or "negative".

The training data contains 7086 sentences, already labeled with 1 (positive sentiment) or 0 (negative sentiment). The test data contains 33052 sentences that are unlabeled. The submission should be a .txt file with 33052 lines. In each line, there should be exactly one integer, 0 or 1, according to your classification results.

I will use 3 approaches for this:

Approach 1 : Just using google's word2vec weights built on google news

Approach 2 : Fine Tune the weights from google using some extra convolutional layers

Approach 3 : Just using deep learning without pre-trained weights
