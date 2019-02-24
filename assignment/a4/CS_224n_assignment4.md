## Assignment 4

### Prob 1. Neural Machine Translation with RNNs

#### (g)

The mask make the attention score maxtrix padding position is -inf, during the softmax calculate, the $e^{-inf} \approx 0$, so the attention weight of <PAD> token is zero. We do that because we want the real source sequence to be attened not the padded sequence, the <PAD> token don't have any information about the real source sequence.

#### (i)

The model's BLEU score of test corpus is 22.197.

#### (j)

The dot product attention is similar with the multiplcative attention, the dot product may be faster than the multipicative attention, but the $s_t$ and $h_i$ should have the same dimension. So I think multipicative attention is more flexible and general.

As for the additive attention, multiplicative attention is faster and more space-efficient in practice as it can be implemented more efficiently using matrix multiplication. It is said the additiva attention is perform better for larger dimension.

### Prob 2. Analyzing NMT Systems



  