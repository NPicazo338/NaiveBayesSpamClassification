# Code

Naive Bayes spam message classification project written in R (RMarkdown).

The Naive Bayes model is trained and tested using cleaned text. The dataset is cleaned of punctuation, capital letters, stopwords and extra white spaces. The text is also stemmed. Stemming is the process of converting different variations (inflections) of a word to its root word. For example, stemming walked, walking, and walks to walk. To further clean the sets, the words that are approximately unique to each SMS message (found in a small subset of messages) are removed. These words do not hold much significance in the determination of spam. The cleaned dataset is then reduced in complexity by tokenizing the text and split into train and test subset.

The training and testing sets are also printed using wordclouds to give us a visual method to identify differences between the train and test sets.