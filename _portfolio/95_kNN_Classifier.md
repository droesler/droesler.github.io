---
title: "K-Nearest Neighbors Classifier (2020)"
excerpt: "This code was created to classify a subset of the [20 newsgroups text dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) from sci-kit learn. Posts drawn from the 'talk.politics.guns', 'talk.politics.mideast', and 'talk.politics.misc' were converted to a bag of words representation, and classified using a 'from scratch' kNN implementation."
collection: portfolio
---

This code was created to classify a subset of the [20 newsgroups text dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) from sci-kit learn. Posts drawn from the 'talk.politics.guns', 'talk.politics.mideast', and 'talk.politics.misc' were converted to a bag of words representation, and classified using a kNN implementation.

[Github repository link to my code](https://github.com/droesler/NLP_Projects_Portfolio/tree/main/kNN_Classifier)

### About the code

The format for launching the script is:  

```build_kNN.py training_data test_data k_val similarity_func sys_output```

where ```training_data``` is train.vectors.txt, ```test_data``` is test.vectors.txt, ```k_val``` is the number of nearest neighbors used to make a classification decision, ```similarity_func``` is 1 for Euclidean distance and 2 for cosine similarity, and ```sys_output``` is the classification results for the train and test data.

| <img src="/images/knn_results.png" alt="/images/knn_results.png" width="500"/> | 
|:--:| 
| *kNN classifier test accuracy by k values and similarity functions.* |

