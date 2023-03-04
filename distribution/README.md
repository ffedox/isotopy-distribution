# Distribution learning

Label distribution learning [(Geng, 2016)](https://arxiv.org/pdf/1408.6027.pdf) involves modeling the probability distribution of a target variable, rather than just predicting a single value. This is achieved by using a sigmoid activation after a linear layer to predict multiple outputs. Instead of discretizing the output of the sigmoid function into binary classes, the outputs are kept as continuous values between 0 and 1.

## Contents

1. [bert_distrib_with_segments.ipynb](https://github.com/ffedox/nlp/blob/main/distribution/bert_distrib_with_segments.ipynb): label distribution learning at segment level.
2. [bert_distrib_with_subtitles.ipynb](): label distribution learning at subtitle level.
