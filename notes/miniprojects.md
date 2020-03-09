# Collection of stuff for MP presentation...


## Project 1 - Interactive Analysis of (Word) Vector Embeddings (IAVE)


### interesting points

* no ground truth - the meaning of words always comprises subjective aspects
* interpreting embeddings and understanding the encoded grammatical and semantic relations between words is useful, but challenging
* Context can also handle stemming for you – the network will likely learn similar word vectors for the words “ant” and “ants” because these should have similar contexts.
* *2v learns on so-called "sentences" (sequences of tokens within a document), but the sentences don't have to consist of words - any sequence of signals can be processed 
  - click streams for user behavior classification / prediction, which is also useful in recommendation
  - leads to *vector representations for products, content, and ads.*
  - e.g. prod2vec ()
  - *architecture, style and feel* of an Airbnb listing



### Reading

* [Skip gram explained](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)
* [IAVE Paper](https://graphics.cs.wisc.edu/Papers/2018/HG18/embeddings_preprint.pdf)



### Websites / Demos / Slides

* [IAVE Website](https://graphics.cs.wisc.edu/Vis/EmbVis/)
* [IAVE Slides](https://www.slideshare.net/gleicher/interactive-analysis-of-word-vector-embeddings)


### Tasks

* learning how to interpret similarity in the vector space
* understanding the influence of source corpora on the resulting embeddings

