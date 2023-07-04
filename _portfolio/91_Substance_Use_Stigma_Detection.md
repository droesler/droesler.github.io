---
title: "Substance Use Stigma Detection System for Reddit Data (2022)"
excerpt: "System that leverages contextual embeddings combined with affective, social, and behavioral features to classify instances of substance use stigma in Reddit posts."
collection: portfolio
---

System that I developed for NIH-funded project at the University of Washington School of Medicine Department of Biomedical Infomatics. 

## Abstract
Stigma surrounding substance use can result in severe negative consequences for physical and mental health. To develop effective interventions, identifying situations in which stigma occurs and characterizing its impact are critical. As part of a project to identify facilitators of substance use stigma reduction and to inform the development of interventions for substance use disorder, this study leverages social media data to identify content with a high probability of containing stigma. We create an annotated corpus of 2,214 Reddit posts from subreddits relating to substance use. We train a set of binary classifiers, in which each classifier detects one of three stigma types: Internalized Stigma, Anticipated Stigma, and Enacted Stigma. By combining RoBERTa contextual embeddings and affective, social, and behavioral features, we produce systems that identify instances of substance use stigma for all three stigma types and outperform RoBERTa-only baselines by up to 6.45 macro F1.

- [Pre-print (12/15/2022) version of the paper](https://github.com/droesler/droesler.github.io/blob/master/files/stigma_paper_preprint_12_15_2022.pdf).

- [Github repository link.](https://github.com/atchen3/stigma_detection)
  
| <img src="/images/stigma_model.PNG" alt="/images/stigma_model.PNG" width="500"/> | 
|:--:| 
| *Architecture of the proposed hybrid model.* |
