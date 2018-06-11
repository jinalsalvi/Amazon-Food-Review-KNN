# Amazon-Food-Review-KNN

"# 1 Introduction\n",
    "This python notebook for Amazon food reviews polarity prediction based on the given review data by applying K Nearest Neighbors (KNN) algorithm. To build generalized prediction model first step should be necessary cleaning of data as a part of data preprocessing. \n",
    "\n",
    "We will perform following data preprocessing. \n",
    "\n",
    "* Removing Stop-words\n",
    "* Remove any punctuations or limited set of special characters like , or . or # etc.\n",
    "* Snowball Stemming the word \n",
    "* Convert the word to lowercase\n",
    " \n",
    "Once we the data is cleaned to be processed we'll use below Feature generation techniques to convert text to numeric vector.\n",
    "1. Bag Of Words (BoW)\n",
    "1. Term Frequency - inverse document frequency (tf-idf)\n",
    "1. Word2Vec\n",
    "1. tf-idf weighted Word2Vec\n",
    "\n",
    "Using KNN algorithm we will build model to predict review polarity for each technique. \n",
    "\n",
    "**Objective: Given a review determine whether a review is positive or negative, by appling KNN algorithm and deciding the best Feature generation technique for given problem.**\n",
    "\n",
    "\n"
