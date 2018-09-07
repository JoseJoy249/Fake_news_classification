Fake news is a major problem that has widespread social and political implications. In this paper, we analyze various existing techniques that are used for fake news detection. We propose a novel web-assisted ensemble model that smartly combines the output of a multilayer neural network and a real-time web search to accurately classify news. Our final model uses a combination of n-grams, TF-IDF , Non-negative Matrix Factorization and Latent Dirichlet Allocation as inputs to a Multilevel Perceptron. Based on the confidence level of the MLP we invoke a secondary classifier that makes use of real-time web search to classify the news based on a given headline. For this paper we also created a new labeled dataset for fake news classification, which we have named Beautiful Liar, this was combined with various other open source datasets to come up with a corpus of over 450K news articles, this final corpus was used to train and test our model. Our model was able to achieve an overall accuracy of around 86% with a BER of 0.13.%