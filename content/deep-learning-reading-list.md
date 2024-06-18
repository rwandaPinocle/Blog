---
title: "Deep Learning/Machine Learning Reading List"
date: 2024-06-07T22:22:01-07:00
draft: false
---

# Transformer Models

[Neural Networks Series](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi):
A well crafted and highly visual walkthrough of modern neural networks by 3Blue1Brown, culminating in an explanation of GPT models.

[Attention Is All You Need](https://arxiv.org/pdf/1706.03762):
This paper is the birth of the transformer model, which proceeded to completely take over deep learning.

[An Image Is Worth 16x16 Words](https://arxiv.org/pdf/2010.11929):
Dosovitskiy et al. showed that unmodified transformers could handle image data as well as text data and still acheive state of the art results.

[Let's build GPT](https://youtu.be/kCc8FmEb1nY?feature=shared):
Andrej Karpathy's tutorial on building a GPT model from scratch in Pytorch.

# Embedding Models

[Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781):
This paper introduced the first major text embedding model called Word2Vec.
Despited being somewhat dated at this point, it's quite a famous paper and some of it's examples are still discussed today.

[Vectoring Words](https://www.youtube.com/watch?v=gQddtTdmG_8):
Computerphile's explanation of word vectors.

[How AI 'Understands' Images (CLIP)](https://youtu.be/KcSXcpluDe4?feature=shared):
CLIP is a pair of models that map both image and text into the same vector space.
This allows you to do text queries across unlabeled images, which I've found very useful on multiple occasions.
It's a very handy foundation model that other models often build off of, such as DALLE, Stable Diffusion, and others.

# ML Engineering Tools

[Pytorch](https://pytorch.org/) and [Tensorflow](https://www.tensorflow.org/):
The industry standard tools for training neural networks.
These days I find Pytorch to be more popular.

[ONNX](https://github.com/onnx/onnx):
ONNX is tool for deploying models on platforms that aren't well supported by Pytorch and Tensorflow, such as C++, Java, JS, Mobile, and Browsers.

# Misc 

[How I got into deep learning, by Vikas Paruchuri](https://www.vikas.sh/post/how-i-got-into-deep-learning):
One man's roadmap from going zero to hero in machine learning.

[Quantization](https://huggingface.co/docs/optimum/en/concept_guides/quantization):
The process of converting a model's weights from `float32` to `float16` or smaller.
Lowers memory requirements and accelerates inference at the cost of accuracy.
I've read of some people trying to go all the way down to [4 bit(!?) floats](https://www.intel.com/content/www/us/en/developer/articles/technical/accelerating-language-model-inference-on-your-pc.html).

# Random Andrej Karpathy Stuff

[A Recipe for Training Neural Networks](https://karpathy.github.io/2019/04/25/recipe/)
A solid recommendation list I come back to whenever I have to train a neural net.

[The Unreasonable Effectiveness of RNNs](https://karpathy.github.io/2015/05/21/rnn-effectiveness/):
An excellent primer on LSTMs.

[Interview with Lex Fridman](https://youtu.be/cdiD-9MMpb0?feature=shared):
An interesting 3+ hour interview with Andrej and Lex Fridman.
Andrej shares a lot of good commentary on the current state of deep learning.