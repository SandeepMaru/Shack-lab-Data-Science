# Shack-lab-Data-Science
#Problem statement:

1. The goal is to understand the relationship between house features and how these variables affect the house price.
2. Matching of Amazon and Flipkart Products


Libraries & Frameworks Used in Task 1
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Standardscaler (Scaling)
6. Linear Regression
7. Ridge 
8. DecisionTreeRegressor
9. RandomForestRegressor
10. KNeighborsRegressor
11. SVR
12. ExtraTreesRegressor
13. RandomizedSearchCV (Hyperparameter Tuning)


Among all model RandomForestRegressor gives the higest accuracy of 78% and again to improve its accuracy with the help of RandomizedSearchCV hyperparameter tunning is done and the accuracy is now around approx 80% .



Libraries & Frameworks Used in Task 2
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. String
6. Nltk
7. Stopwords
8. PorterStemmer
9. WordNetLemmatizer
10. CountVectorizer
11. TfidfVectorizer
12. Cosine_similarity

# Cleaning Text

Cleaning the text and then convert all text in lower case, converting text to words after converting in words only taking the words from that list which are alphanumeric and from that removing all kind of punctuation and special character and applying stemming on that words to get the cleaned text from list.


# Convert text to vectors

Converting text to vectors by using TfidfVectorizer in this case and finding top 5000 words from that list and converting to vectors.


# Finding Similarity

With the help of cosine_similarity finding the similar vectors on the basis of index number and with the help of enumerate function will fix the index position to find similar vectors from array of vectors.
