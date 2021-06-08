# stats170
Repo for Winter-Spring 2021 Stats 170 Project for Group 5, consisting of Irene Kim, David Gonzales, and Kerry Liu. 


## Organization of Final Submission Files

The model that we'll be submitting is a logistic regression classifier trained using tf-idf. We trained our model using with the documents provided by FFF Enterprises. After 

Our model is up to bigrams using a regularization term of 10 in sklearn's logistic regression classifier.

The work that we're submitting is contained within the final_notebook.ipynb Jupyter notebook, and requires fulldocs.csv and important_words.txt to train. With these three files, you simply need to run everything in the notebook in order. Additional descriptions are contained within the notebook itself.

## Additional Files

The main branch also contains additional files showcasing our work.
- The doc2vec.ipynb notebook showcases our attempts to train a logistic regression classifier using doc2vec vectors.
- The tf_idf_with_logistic_regression.ipynb notebook showcases how we trained a logistic regression classifier using tf-idf vectors.
- The tfidfnaivebayes.ipynb notebook showcases how we trained a Naive Bayes classifier with tf-idf.
- largedocuments and document_label_mapping notebooks show how we pushed our data into our database. 
- wordcloudandbarplots contains some visualizations we made for presentations. 
