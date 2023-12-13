# ALTEGRAD-Labs
This reposiotry is dedicated for my 3 session of ALTEGRAD's Labs : 
### Lab1 : Neural Machine Translation
In this lab, you will learn about sequence to sequence (seq2seq) architectures. More precisely, we will
implement the Neural Machine Translation (NMT) model described in [4] using Python and PyTorch, the only difference is that we will be using non-stacked RNNs.
We will train our model on the task of English to French translation, using a set of sentence pairs from http://www.manythings.org/anki/, originally extracted from the Tatoeba project: https://tatoeba.org/eng/.
Our dataset features 136,521 pairs for training and 34,130 pairs for testing, which is quite small, but enough for the purpose of this lab.
### Lab2 : Transfer learning for NLP
Transfer learning that is, solving tasks with models that have been pretrained on very large amounts of data, was a game changer in many deep learning tasks. In NLP, while annotated data are scarce, raw text is virtually unlimited and readily available. Thus, the ability to learn good representations from plain text could greatly improve general natural language understanding. Learning without labels is enabled via self-supervised learning, a setting in which a system learns to predict part of its input from
other parts of its input.
### Lab3 : NLP Frameworks
Transformer models have been the predominant deep learning models used in NLP for the past several years, with well-known exemplars in GPT-3 from OpenAI and its predecessors, the Bidirectional Encoder Representations from Transformers model (BERT) developed by Google, and many other models and variants besides. Following the paper “Attention is All You Need” from 2017, the unofficial milestone marking the start of the “age of transformers”, transformer models have gotten bigger, better, and much closer to generating text that can pass for human writing, as well as improving substantial on statistical loss metrics and standard benchmarks.
In order to pretrain and finetune transformer based language models, multiple frameworks and libraries have been introduced such as Fairseq[7] and HuggingFace’s transfor 
