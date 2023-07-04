---
title: "Decision Tree Classifier (2020)"
excerpt: "
The script builds a decision tree 'from scratch' using the training data (a subset of the [20 newsgroups text dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) from sci-kit learn), classifies the training and test data, and calculates the accuracy."
collection: portfolio
---

This code was used to classify a subset of the [20 newsgroups text dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) from sci-kit learn. Posts drawn from the 'talk.politics.guns', 'talk.politics.mideast', and 'talk.politics.misc', converted to a bag of words representation, and classified using a decision tree implementation.
 
The script builds a decision tree from the training data, classifies the training and test data, and calculates the accuracy.

[Github repository link to my code](https://github.com/droesler/NLP_Projects_Portfolio/tree/main/Decision_Tree_Classifier)

### About the code

The format for launching the script is:  

```build_dt.py training_data test_data max_depth min_gain model_file sys_output```

where ```training_data``` is train.vectors.txt, ```test_data``` is test.vectors.txt, ```max_depth``` is the maximum depth of the tree, ```min_gain``` is the minimal information gain for each split, ```model_file``` is the filename for the output model, and ```sys_output``` is the classification results for the train and test data.

| <img src="/images/dt_class_results_table.png" alt="results_table.png" width="500"/> | 
|:--:| 
| *Decision tree results when min_gain=0.* |
