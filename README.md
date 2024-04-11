# Neural-Machine-Translation
In this project, we performed machine translation using two deep learning approaches: a Recurrent Neural Network (RNN) and a Transformer.

Here are some helpful links:
1. [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)
2. [NLP From Scratch: Translation with a Sequence to Sequence Network and Attention (Pytorch tutorials)](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)

## Recurrent Neural Network (RNN)
Here are some helpful links:
1. [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf)
2. [Explanation of LSTM's & GRU's](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21)
3. [Different types of Attention in Neural Networks](https://gotensor.com/2019/07/06/different-types-of-attention-in-neural-networks/)
4. [Attention and its Different Forms](https://towardsdatascience.com/attention-and-its-different-forms-7fc3674d14dc)

### Model Generation examples

**Source sentence:** <start> tom no esta preocupado . <end>
**Target sentence:** <start> tom isn t worried . <end>
**Predicted sentence:** <start> tom isn t worried . <end>

**Source sentence:** <start> hemos estado aqui antes . <end>
**Target sentence:** <start> we ve been here before . <end>
**Predicted sentence:** <start> we ve been here before . <end>

**Source sentence:** <start> abrelo , por favor . <end>
**Target sentence**: <start> please open it . <end>
**Predicted sentence:** <start> please come in . <end>

**Source sentence:** <start> no me gusta ninguno de ellos . <end>
**Target sentence:** <start> i like none of them . <end>
**Predicted sentence:** <start> i don t like any of them . <end>

**Source sentence:** <start> lo hice por tom . <end>
**Target sentence:** <start> i did it for tom . <end>
**Predicted sentence:** <start> i did that for tom . <end>

### Evaluation
**Loss:** 1.8524.
**BLEU 1-gram:** 0.297967.
**BLEU 2-gram:** 0.083336.
**BLEU 3-gram:** 0.060941.
**BLEU 4-gram:** 0.057988.

Read more about Bleu Score at:
1. https://en.wikipedia.org/wiki/BLEU
2. https://www.aclweb.org/anthology/P02-1040.pdf

## Transformer
Here are some helpful links:
1. [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
2. [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
3. [Transformers From Scratch](http://peterbloem.nl/blog/transformers)

### Model Generation examples

**Source sentence:** <start> probaremos a hacerlo otra vez . <end>
**Target sentence:** <start> we ll try again . <end>
**Predicted sentence:** <start> we ll try again . <end>

**Source sentence:** <start> dejemos de perder tiempo . <end>
**Target sentence:** <start> let s stop wasting time . <end>
**Predicted sentence:** <start> let s stop wasting time . <end>

**Source sentence:** <start> lamento lo que paso . <end>
**Target sentence:** <start> i regret what happened . <end>
**Predicted sentence:** <start> i m sorry than happened . <end>

**Source sentence:** <start> no puedo confiar en vosotros . <end>
**Target sentence:** <start> i can t trust you . <end>
**Predicted sentence:** <start> i can t trust you . <end>

**Source sentence:** <start> solo era un sueno . <end>
**Target sentence:** <start> it was only a dream . <end>
**Predicted sentence:** <start> it was just a dream . <end>

### Evaluation
**Loss:** 1.3676.
**BLEU 1-gram:** 0.299091.
**BLEU 2-gram:** 0.084177.
**BLEU 3-gram:** 0.061698.
**BLEU 4-gram:** 0.058867.
