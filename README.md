# NLPlay-with-Transformers
-----------
The first phase of the project was to use Natural Language Processing for Sentiment Analysis. We were given resources to gain the basic knowledge about Machine learning required for the project in week 1. First we used simple Feed Forward Neural Networks using Bag Of words and then in week 3 we modified that model by using RNN and then later LSTM and GRU.

--------
# Week 1
------
1. Learned the basics of Python.
2. Covered basic libraries like numpy, pandas, matplotlib and pytorch.
3. Learned how Neural Networks work.
4. Covered the theory of how NLP works and the different steps in it
5. Covered the basic codes of nltk.
6. Introduction to Github and Google Colab.

------
# Week 2
------
1. Went deeper into Natural Language Processing.
2. Learned about Word Embeddings.
3. Created a Sentiment Classifier using Feed Forward NEural Network.

**Creating a Neural Network for classifying positive and negative reviews trained on the IMDB dataset of 50,000 reviews.**
1. Saved the csv file on github and downloaded it on colab.
2. Completed word tokenization.
3. Removed stopwords.
4. Completed Stemming.
5. Divided file into 70% training and 30% testing.
6. Used BOW vectorization.
7. Implemented a Feed forward NN with 2 hidden layers of 500 neurons each.
8. Used ReLu as activation function and cross entropy for loss function.
9. Used Stochastic Gradient Descent with different batch sizes and learning rates.
10. Maximum accuracy achieved: 87.87%

-----
# Week 3
-----
1. Learned the working of Recurrent NN.
2. Understood the mathematics used in RNN.
3. Modified the FFNN model using RNN.
4. Achieved accuracy of : 78.23% 
5. Understood the working and mathematics of LSTM.
6. Modified and made a LSTM based model.
7. Achieved an accuracy of : 93.5%
8. Understood the working of GRU.
9. Implemented the GRU model. Acuuracy achieved: 93.91% 

-----
# Week 4
-----
This was a buffer time. Tried to cover the work left in Week 2 and 3.

----
# Week 5
----
1. Understood what is Attention and how it works in Deep Learning.
2. Understood the basics of Transformers (BERT and others) and their working.
3. Started making the Sentiment Classifier using BERT.

-----
# Week 6
----
1. Completed the Sentiment Classifier using BERT (dataset of 50000 reviews).
2. Achieved an accuracy of 93.05%
3. To compare the accuracies and speed of BERT, RoBERTa and DistilBERT I used only the first 5000 reviews of the dataset.
4. Achieved accuracies- BERT- 90.27%
                        RoBERTa- 91.87%
                        DistilBERT- 90.73%
5. One observation- The DistilBERT trainer(9 min 33 sec) program took almost half the time as of BERT(17 min 53 sec) and RoBERTa(18 min 47 sec). The reason is because DistilBERT retains only half of the layers from BERT. It uses half parameters but has approximately the same accuracy.

-----
# Week 7
-----
This was a buffer Week. Completed pending tasks.

----
# Week 8
----
1. Understood the working of GPT-2 and T5 transformers in the domain of text generation.
2. Created a custom dataset(science.csv)
