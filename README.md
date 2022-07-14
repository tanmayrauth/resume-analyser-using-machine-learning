# resume-analyser-using-machine-learning

It parases the resume and categorises the resume to a particular category(ML, Backend, Data Science, Blockchain) based on the keywords used in it. 
These keywords are passed into the trained model to identify the category.

Parsing the Resume in pdf format and fetching the text data out of it. Cleaning the data using regular expressions and tokenised text data using NLTK library.
Used TfidfVectorizer for converting the text data into vectors. And trained those vectors data on the KNNClassifier using the sklearn library.

The train:test percentage is 80:20. Model has an accuracy rate of around 97%


