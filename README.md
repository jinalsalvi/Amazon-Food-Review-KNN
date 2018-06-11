# Amazon-Food-Review-KNN

# Introduction  
     This python notebook for Amazon food reviews polarity prediction based on the given review data by applying K Nearest Neighbors (KNN) algorithm. To build generalized prediction model first step should be necessary cleaning of data as a part of data preprocessing.    
        
     We will perform following data preprocessing.    
        
     * Removing Stop-words   
     * Remove any punctuations or limited set of special characters like   or . or # etc.   
     * Snowball Stemming the word    
     * Convert the word to lowercase   
         
     Once we the data is cleaned to be processed we'll use below Feature generation techniques to convert text to numeric vector.   
     1. Bag Of Words (BoW)   
     1. Term Frequency - inverse document frequency (tf-idf)   
     1. Word2Vec   
     1. tf-idf weighted Word2Vec   
        
     Using KNN algorithm we will build model to predict review polarity for each technique.    
        
     **Objective: Given a review determine whether a review is positive or negative  by appling KNN algorithm and deciding the best Feature generation technique for given problem.**   
        
       
