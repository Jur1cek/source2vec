# Source2vec
This repository contains source code embeddings for various programming languages.

Source code files are preprocessed using standard tokenization (it could not be ideal solution for source code), this is work in progress. Also we are working on enhancing embeddings with ASTs and PDGs.

## Java
Created from 1792 million tokens
Window (context) size 5

#### Word2vec
TBA
#### FastText
TBA
#### GloVe
TBA


## Python
Created from 838 million tokens
Window (context) size 5
Vocabulary used http://dizp.fufygen.eu/embeddings/python/python_vocab.txt.zip

#### Word2vec
http://dizp.fufygen.eu/embeddings/python/word2vec/python_word2vec.zip

#### FastText
#### GloVe
http://dizp.fufygen.eu/embeddings/python/glove/python_glove_vectors.bin.zip
http://dizp.fufygen.eu/embeddings/python/glove/python_glove_vectors.txt.zip


## C
Created from 6589 million tokens
Window (context) size 10

#### Word2vec
TBA
#### FastText
TBA
#### GloVe
TBA


## C+
TBA
#### Word2vec
TBA
#### FastText
TBA
#### GloVe
TBA

...if you need another languages or different params just open issue

##### Common parameters
Vector size 64 - vocab is smaller than usual vocabs used in NLP tasks, so 64 is just fine
Minimum number of occurrences 10 - under 10 these are mainly prints and rare variable/method/class names

### How to load embeddings?
TBA

### Dimensionality reduction and visualisation of embeddings
TBA


Paper comming out soon.
