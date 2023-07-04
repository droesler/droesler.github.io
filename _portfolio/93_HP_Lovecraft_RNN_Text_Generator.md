---
title: "H.P. Lovecraft RNN Text Generator (2021)"
excerpt: "A GRU-based character-level language model trained on a corpus of [the fiction of H.P. Lovecraft](https://www.hplovecraft.com/writings/texts/)."
collection: portfolio
---

A GRU-based character-level language model trained on a corpus of [the fiction of H.P. Lovecraft](https://www.hplovecraft.com/writings/texts/).

Run the demo notebook and generate new texts in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/droesler/HP_Lovecraft_RNN_Text_Generator/blob/master/HPL_gen_demo.ipynb)

[Github repository link to my code](https://github.com/droesler/HP_Lovecraft_RNN_Text_Generator)

A sample output:
```
The gibbous moon shine of the crypts directly down in the dark passageway leading to unguessed signs and sometimes floated from incredible planets of the region had taught him to understand the repeated floor.
And the sight of the walls, for the precipice and the precipitous hills beyond Arkham were dead, and the great black secret of the house was out of sight I saw the city and the placid spawn of the planted nightmare spheres of low cloths.
The proper courses were now terrific, and I saw that I must be a kind of harmless stupidity to detail a wholesome life in the sunset.
They were all silent and realistic tears, and it was purely profound and perplexed to feed a curious level past the limestone hill bass rock whose trees had been released and filled with the tubes and sound-bog noises and children with a gleaming rows of precipitous laws of those who had once dwelt the papers had come down from over the side and a low, white form of many generations of wild planet with domestic substitution.
```

### About the code

A 2-layer Gated Recurrent Unit (GRU) autoregressive character language model built in TensorFlow, trained for 30 epochs on 0.5 million tokens of text.

The notebook used to train the model can be found [here](https://github.com/droesler/HP_Lovecraft_RNN_Text_Generator/blob/main/HPL_char_LM_training.ipynb).

The model:
```
Model: "my_model"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
embedding (Embedding)        multiple                  23552     
_________________________________________________________________
gru (GRU)                    multiple                  3938304   
_________________________________________________________________
gru_1 (GRU)                  multiple                  6297600   
_________________________________________________________________
dense (Dense)                multiple                  94300     
=================================================================
Total params: 10,353,756
Trainable params: 10,353,756
Non-trainable params: 0
_________________________________________________________________
```

This project was based on the TensorFlow RNN tutorial that can be found [here](https://www.tensorflow.org/text/tutorials/text_generation).


