# Sentiment-Analysis
Getting the sentement of a given text or a sentence

# I try to explain the flow in a high level
1) Read the files from the local computer or u can clone this repo.
2) Run load_text function and it will load all the data present in the txt file.
3) Run the preprocessing the function:
  a) first tokenize the txt data into words.
  b) Remove Punctuation from the data.
  c) Remove the stopwords from the data.
  d) Get only alpha numeric values.
  e) Normalize the data(lower case)
  f) Take the words which are greater then 1.
 4) Create Bag Of Words/Dict/vocaboulary for the sentement analysis.
 5) Save that vocaboulary to local computer.
 6) Now read all the txt files with negative and positive reviews and take only the woeds which are present in the Bag of words.
 7) make the labels also while reading neg and pos review files.
 8) Split data into train and test for training.
 9) Pass the training data in the form of vectors of zeros and ones.
 10) By keras sequential model build a model which will predict the sentement.
