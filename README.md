# Semantic_Text_Similarity

### Problem Statement

•	The data contains a pair of paragraphs. These text paragraphs are randomly sampled from a raw dataset. Each pair of sentences may or may not be semantically similar. The candidate is to predict a value between 0-1 indicating the similarity between the pair of text . A sample of a similar dataset will be used as test data, therefore it’s crucial to the model solution using provided dataset.

•	Build an algorithm/model that can quantify the degree of similarity between the two text-based on Semantic similarity. Semantic Textual Similarity (STS) assesses the degree to which two sentences are semantically equivalent to each other. 1 means highly similar 0 means highly dissimilar

### Proposed Approach
1.	Import Library
2.	Read Data-Set
3.	Preprocessing of text1 & text2
  *	Removing punctuations like .,!$()*%@
  *	Removing stop words
  *	Lower casing
  *	Tokenization
  *	Stemming
  *	Lemmatization

4.	Word Embedding Algorithms
  *	Word embeddings are in fact a class of techniques where individual words are represented as real-valued vectors in a predefined vector space. Pre-trained word embeddings are also available in the word2vec code.google page.
  *	In this I am using Google news pre trained vectors and compare similarity between text1 & text2 using n_similarity method in gensim library which is nothing compares cosine similarity between two
