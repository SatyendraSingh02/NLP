# Sentiment Analysis 
Here we have analyse the sentiments of reviwes given by the customer for a Restaurent.
Sentiment Analysis - It stands for predicting whether the reviews /sentence give sense about positivity or negativity.

*Restaurant_Review_classification.ipynb --Jupyter notebook file 

*Restaurant_Review.tsv -contains the dataset
### Steps Involved

Step-1 importing the required libraries

Step-2 Mounting the drive 

Step-3 Importing the dataset ("Restaurent_reviews.tsv") tsv-tab separated file containing two columns reviews and liked(0/1)

Step-4 Converting Reviews column into list 

Step-5- text-Pre_processing of list 

        1-Lowercase 
        2-Tokenizing each word in the list (providing a token to each word)
        3-removing Stopwords that does not account for meaning or sense of sentence
        4-Removing Punctuations 
        
step-6 -Making the wordcloud based upon frequency(count of token) or words appear in the list    

        1-common Word Cloud 
        2-Positive Word Cloud
        3-Neagtive Word Cloud
        
step-7  Feature engineering (for extracting the features from given list)

        A.creating Vector (as textual data is not trainable and testable)
            1-By using BoW (Bag of word method)-                          {https://medium.com/greyatom/an-introduction-to-bag-of-words-in-nlp-ac967d43b428}
            2-By using TF-IDF(term Frequncy -Inverse document Frequency)
         
Step-8 Applying various Models of Classification of machine learning and finding their Accuracy,precision,Recall score for comparison. And then selecting the model.
       



