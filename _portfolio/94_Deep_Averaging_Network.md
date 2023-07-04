---
title: "Deep Averaging Network (2021)"
excerpt: "A Pytorch implementation of the Deep Averaging Network introduced in Iyyer et al (2015). Performs binary sentiment classification on the [IMDB reviews dataset](http://ai.stanford.edu/~amaas/data/sentiment/)."
collection: portfolio
---

A Pytorch implementation of the Deep Averaging Network introduced in Iyyer et al (2015). Performs binary sentiment classification on the [IMDB reviews dataset](http://ai.stanford.edu/~amaas/data/sentiment/). 
 
[Github repository link to my code](https://github.com/droesler/NLP_Projects_Portfolio/tree/main/Deep_Averaging_Network)

### About the code
Dependencies:
See environment.yml for the Conda environment.

Command line parameters:
```
    # model arguments
    parser.add_argument('--embedding_dim', type=int, default=300)
    parser.add_argument('--hidden_dim', type=int, default=300)
    # training arguments
    parser.add_argument('--batch_size', type=int, default=64)
    parser.add_argument('--seed', type=int, default=572)
    parser.add_argument('--num_epochs', type=int, default=15)
    parser.add_argument('--patience', type=int, default=None)
    parser.add_argument('--L2', action="store_true")
    # data arguments
    parser.add_argument('--data_dir', type=str, default='/data')
    parser.add_argument('--vocab_size', type=int, default=20000)
    parser.add_argument('--padding_index', type=int, default=1)
```
Example output:

| <img src="/images/DAN_output.png" alt="/images/DAN_output.png" width="1000"/> | 
|:--:| 
| *Results for --num epochs 12 --patience 3 --L2.* |

