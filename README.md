Usage notes

——————————————

This project was developed with the purpose of detecting question similarities and duplicates among the vectors. The data used for the task is Quora's Question Pairs dataset, its link can be found below. Cosine Similarity is used to calculate sent2vec and tf-idf vector similarities. The condition for duplicates is set with a threshold of our choice. As an evaluation metric, the number of correct/incorrect calculations for each vector types can be seen as a comparative performance evaluation.

Packages
- Texthero: Used for pre-processing and TF.IDF vector representation.
- Sent2vec: Used for creating sentence embeddings. (with pandas)
- spicy.spatial.distance: Used for computing distance.

——————————————

 The evaluation metric used in this projects returns either correct or incorrect with relation to the similarity value being is_duplicate or not.

——————————————

Git Hub page: https://github.com/0irelia/Question-Similarity
Quora Question Pairs Dataset: https://www.kaggle.com/quora/question-pairs-dataset
