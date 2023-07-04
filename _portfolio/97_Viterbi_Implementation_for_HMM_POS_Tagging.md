---
title: "Viterbi Implementation for HMM POS Tagging (2020)"
excerpt: "This script reads an HMM file produced by the [MALLET](http://mallet.cs.umass.edu/) machine learning toolkit and uses an implementation of the Viterbi algorithm to find the most probable tag sequence for the text."
collection: portfolio
---
This script reads an HMM file produced by the [MALLET](http://mallet.cs.umass.edu/) machine learning toolkit and uses an implementation of the Viterbi algorithm to find the most probable tag sequence for the text.

[Github repository link to my code](https://github.com/droesler/NLP_Projects_Portfolio/tree/main/Viterbi_Implementation_for_HMM_POS_Tagging)

### About the code

The format for launching the script is:  

```viterbi.py input_hmm test_file output_file```

where ```input_hmm``` is hmm5, which can be found in hmm5.rar, ```test_file``` is test.word, and ```output_file``` is the desired name of the output file.

| <img src="/images/viterbi_output_sample.png" alt="/images/viterbi_output_sample.png" width="1700"/> | 
|:--:| 
| *A sample of the output with the format of: (input) => (trigram POS label) (joint log probability of sequence).* |

