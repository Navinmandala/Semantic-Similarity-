# Semantic-Similarity-
Semantic Similarity Using BERT Transformers
Semantic Similarity Using BERT Transformers



Semantic Similarity, or Semantic Textual Similarity, is a task in the area of Natural Language Processing (NLP) that scores the relationship between texts or documents using a defined metric. Semantic Similarity has various applications, such as information retrieval, text summarization, sentiment analysis, etc.



The concept of semantic similarity is more specific than semantic relatedness, as the latter includes concepts as antonymy and meronymy, while similarity does not. However, much of the literature uses these terms interchangeably, along with terms like semantic distance. In essence, semantic similarity, semantic distance, and semantic relatedness all mean, "How much does term A have to do with term B?" The answer to this question is usually a number between -1 and 1, or between 0 and 1, where 1 signifies extremely high similarity 



Dataset set contains Three Variables i.e [ Text, Reason , Label]

Label variable contains values of 0 and1

0 : means 'not similar'

1 : means 'Similar


Data is already Preprocessed , steps taken
1) balanced dataset
2) Fine Tuning your model with BERT Pretrained weights
3) Fine Tuning BERT model with Hyperparameters Using Keras Tuner
4) Evaluate Your Model By entering texts manually
