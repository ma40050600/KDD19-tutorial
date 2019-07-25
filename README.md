KDD19 Tutorial: From Shallow to Deep Language Representations: Pre-training, Fine-tuning, and Beyond
==================================================================

<h3>Time: Thu, August 08, 2019 - 9:30am - 12:30 pm | 1:00 pm - 4:00 pm</h3>
<h3>Location: Dena’ina Center, 600 W. Seventh Avenue Anchorage, AK 99501</h3>

<span style="color:grey">Presenter: Aston Zhang, Haibin Lin, Leonard Lausen, Sheng Zha, Alex Smola</span><br/>


Abstract
--------
Natural language processing (NLP) is at the core of the pursuit for artificial intelligence, with deep learning as the main powerhouse of recent advances. Most NLP problems remain unsolved. The compositional nature of language enables us to express complex ideas, but at the same time making it intractable to spoon-feed enough labels to the data-hungry algorithms for all situations. Recent progress on unsupervised language representation techniques brings new hope. In this hands-on tutorial, we walk through these techniques and see how NLP learning can be drastically improved based on pre-training and fine-tuning language representations on unlabelled text. Specifically, we consider shallow representations in word embeddings such as word2vec, fastText, and GloVe, and deep representations with attention mechanisms such as BERT. We demonstrate detailed procedures and best practices on how to pre-train such models and  ne-tune them in downstream NLP tasks as diverse as finding synonyms and analogies, sentiment analysis, question answering, and machine translation. All the hands-on implementations are with Apache (incubating) MXNet and [GluonNLP](http://gluon-nlp.mxnet.io/), and part of the implementations are available on [Dive into Deep Learning](https://www.d2l.ai).


Agenda
------

| Time        | Tutor        | Title                                                                    | Slides  | Notebooks  |
|-------------|-------------|------------------------------------------------------------------------|------------|------------|
| 9:30am-10:00am | Alex Smola | Basics of hands-on deep learning                                             || [ndarray](01_ndarray_autograd/ndarray.ipynb), [autograd](01_ndarray_autograd/autograd.ipynb) |
| 10:00am-10:50am | Alex Smola | Neural networks                                    ||  [mlp-method](02_neural_nets/mlp.ipynb) [mlp-scratch](02_neural_nets/mlp-scratch.ipynb) [mlp-gluon](02_neural_nets/mlp-gluon.ipynb) |
| 11:00am-11:45am | Aston Zhang  | Shallow language representations in word embedding           || [word2vec](03_word_embedding/word2vec.ipynb), [approx-train](03_word_embedding/approx-training.ipynb), [GloVe](03_word_embedding/glove.ipynb), [pre-train](03_word_embedding/word2vec-gluon.ipynb) |
| 11:45am-12:30pm | Aston Zhang   | Application                                       || [analogy](04_word_embedding_app/similarity-analogy.ipynb), [sa-rnn](04_word_embedding_app/sentiment-analysis-rnn.ipynb), [sa-cnn](04_word_embedding_app/sentiment-analysis-cnn.ipynb)|
| 12:30pm-1:00pm |    | Lunch break                                                         ||  |
| 1:00pm-2:20pm | Leonard Lausen   | Transformer                                                     ||[transformer](05_transformer/transformer.ipynb)  |
| 2:30pm-3:30pm | Haibin Lin   | Deep language representations with Transformer (BERT)       | [contextual_representations](06_bert/contextual_representations.pdf) |   |
| 3:30pm-4:00pm | Haibin Lin   | Application                                                || [text classification](07_bert_app/bert.ipynb) |
