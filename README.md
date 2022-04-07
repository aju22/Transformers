# Transformers

In sequence-to-sequence problems such as the neural machine translation, the initial proposals were based on the use of RNNs in an encoder-decoder architecture. These architectures have a great limitation when working with long sequences, their ability to retain information from the first elements was lost when new elements were incorporated into the sequence.

Then to deal with this limitation, a new concept were introduced the attention mechanism.

![Attention](https://blog.floydhub.com/content/images/2019/09/Slide36.JPG)

The Transformer model extract features for each word using a self-attention mechanism to figure out how important all the other words in the sentence are w.r.t. to the aforementioned word. And no recurrent units are used to obtain this features, they are just weighted sums and activations, so they can be very parallelizable and efficient.

Research Paper : [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

## This is an implementation of Transformer Attention model using Tensorflow/Keras.
