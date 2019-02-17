## Assignment 4

### Prob 1. Neural Machine Translation with RNNs

#### (g)

The mask make the attention score maxtrix padding position is -inf, during the softmax calculate, the $e^{-inf} \approx 0$, so the attention weight of <PAD> token is zero. We do that because we want the real source sequence be attened not the padded sequence.

#### (i)

The model's BLEU score of test corpus is 22.197.

### (j)

  