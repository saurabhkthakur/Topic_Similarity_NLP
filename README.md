# Topic_Similarity_NLP

## Basic flow:
* Tokenize the sentences after converting them to lowercase
* Depending on the type of encoder, the sentence gets converted to a 512-dimensional vector If we use the transformer, it is similar to the encoder module of the transformer architecture and uses the self-attention mechanism. The DAN option computes the unigram and bigram embeddings first and then averages them to get a single embedding. This is then passed to a deep neural network to get a final sentence embedding of 512 dimensions.
* These sentence embeddings are then used for various unsupervised and supervised tasks like Skipthoughts, NLI, etc. The trained model is then again reused to generate a new 512 dimension sentence embedding.


### Universal Sentence Encoder (State of Art Network)
Universal Sentence Encoder is sentence embedding techniques that has been proposed by Google. sentence embeddings we generate can be used for multiple tasks like sentiment analysis, text classification, sentence similarity, etc
