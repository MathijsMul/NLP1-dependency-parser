# Neural dependency parser

A neural network based dependency parser that uses 50-dimensional vector space embeddings for words, POS-tags, and arc-labels. Following [Chen and Manning (2014)](literature/Chen_Manning.pdf). See the [final report](final-report.pdf) or the [presentation](presentation.pdf) for our findings. Joint work with [Daan van Stigt](https://github.com/daandouwe). Final project for UvA course Natural Language Processing 1. 

## Requirements
```
pip install scikit-learn
```
You need the pretrained glove word2vec mapping (6B), which can be downloaded from http://nlp.stanford.edu/data/glove.6B.zip. It is too big to upload to the github repository, so in your local version of the project, create a folder including the github repository as one folder, and the glove.6B directory as another folder.
