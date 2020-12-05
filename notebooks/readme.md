->pre-processing.ipynb : This notebook includes processing text files to extract text (as a single string) and includes several pre-processing steps like stopwords removal, special character removal etc. At the end it has functions to get tokens from the pre-processed text hence getting a corpus ready for LDA model. This includes the google stop word removal and for that the google_list file has to in the same directory as the notebook.

->Text_rank.ipynb : This contains the text-rank pre-processing. 

->Lda.ipynb : This notebook takes corpus as input and extracts tokens. It mainly contains the training and evaluating the best model part.

->Clustering.ipynb : This notebook was used to cluster the documents based on x-axis. So in addition to the corpus it takes resources coordinates csv file as input.

->Learners_contribution.ipynb : This notebook was used to create the lerner’s contribution corpus.

->Learner_probability.ipynb : This notebook includes classifying of learner’s contribution and getting the probability distribution by using a saved model and dictionary.

->Classifying.ipynb : This notebook has the same functionality of producing the probability distribution but instead of using a saved model it takes corpus that means it has the topic modelling part. This also includes saving of a trained model, dictionary and pyLDAvis html file. 

