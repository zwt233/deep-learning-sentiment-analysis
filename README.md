# deep-learning-sentiment-analysis
deep-learning-sentiment-analysis is an NLP project that compares three different models for binary sentiment classification. 

## Data
deep-learning-sentiment-analysis uses Stanford's [Large Movie Review Dataset] (http://ai.stanford.edu/~amaas/data/sentiment/). It consists of sets for positive train, negative train, positive test, and negative test, each of which has 12,500 reviews, along with 50,000 unlabeled reviews for unsupervised learning, for 100,000 total reviews. Each review is comprised of multiple sentences.

## Models
deep-learning-sentiment-analysis utilizes three different models for sentiment analysis:
* SentimentAnalysisCoreNLP.java: Recursive Neural Tensor Network via [Stanford CoreNLP] (http://nlp.stanford.edu/sentiment/code.html)
* sentiment_analysis_gensim.ipynb: Doc2Vec embedding via [gensim] (https://radimrehurek.com/gensim/models/doc2vec.html)
* sentiment_analysis_tensorflow.ipynb: Convolutional Neural network via [TensorFlow] (https://www.tensorflow.org/)

## Academic Background
* Dataset: [Maas et al. 2011] (http://ai.stanford.edu/~amaas/papers/wvSent_acl2011.pdf)
* Recursive Neural Tensor Network: [Socher et al. 2013] (http://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf)
* Word2Vec: [Mikolov et al. 2013] (https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
* Doc2Vec: [Le and Mikolov 2014] (https://cs.stanford.edu/~quocle/paragraph_vector.pdf)
* Convolutional Neural Network: [Kim 2014] (https://arxiv.org/pdf/1408.5882v2.pdf)

## Software Dependencies
deep-learning-sentiment-analysis is written in Python 2.7 in a Jupyter notebook and uses several common software libraries, most notably Stanford CoreNLP, gensim, and TensorFlow. In order to run it, you  must install the follow dependencies:
* [Python] (https://www.python.org/)
* [Jupyter] (http://jupyter.org/)
* [Stanford CoreNLP] (http://stanfordnlp.github.io/CoreNLP/)
* [gensim] (https://radimrehurek.com/gensim/)
* [TensorFlow] (https://www.tensorflow.org/)
* [NumPy] (http://www.numpy.org/)
* [BeautifulSoup] (https://www.crummy.com/software/BeautifulSoup/)

## License
This project uses the [Apache 2.0 License] (https://github.com/charlescc9/deep-learning-sentiment-analysis/blob/master/LICENSE).
