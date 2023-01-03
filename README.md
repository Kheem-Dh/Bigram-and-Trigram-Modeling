# Bigram-and-Trigram-Modeling

## Find the code in Tag (Named Bigram)

#### Took the shared "Unigram Modeling.IPYNB" as the starting point for this task. 
#### It builds a unigram language model. 
#### And build the bigram and the trigram language models.

#### Took a corpus realdonaldtrump.csv. Take the tweets out. Remove any links and did the following:

##### 1) Split data into 80% training and 20% test sets.

##### 2) Remove punctuation marks. 

##### 3) Remove the newline characters.

##### 4) Remove stopwords.

##### 5) Use the n-grams module from nltk.util package to build bigrams and trigrams.

##### 6) Find the frequencies of bigrams and trigrams in the corpus. 
##### Tabulate them and show the histogram. Compare it with Zipf's Law.

##### 7) Do Add-1 smoothing (Laplace) as explained in the slides.

##### 8) Build a dictionary showing bigram and trigram probabilities against each sorted in increasing order.

##### 9) Retabulate the reconstituted counts for the bigrams and the trigrams.

##### 10) Redo the histogram and compare it again with Zipf's Law.

##### 11) Take a four-word string as the test sample and find both its unigram, bigram, and trigram perplexities.

##### 12) Natural Langauge Generation Task: Based on step 7, build CDF (Cumulative Distribution Function).
 ##### Generate a random number and compare it with the CDF. 
##### Pick the word whose CDF value is closest to it and return it as the generated text.

##### 13) Build the Shannon game as discussed in the class. 
##### Predict the last word (hide it during prediction time) of the tweets in the test set based on one word before 
##### (Bigram modeling), and two words before (trigram modeling), and evaluate the results using accuracy.
