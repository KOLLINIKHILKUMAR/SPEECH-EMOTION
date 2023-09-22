\*\*\*\*\*\* SPEECH EMOTION DETECTION \*\*\*\*\*\*
==================================================

  

PYTHON--------JUPYTER--------FRONTEND---------DEPLOYMENT-(FLASK)

  
  

ABOUT
-----

Speech emotion detection is the process of analyzing audio data to determine the emotional state of the speaker, often using machine learning algorithms.
---------------------------------------------------------------------------------------------------------------------------------------------------------

  

#### IN THIS APPLICATION WE DETECT THE EMOTION OF TEXT BY USING MODELS.

#### In this project we are given a dataset along with the four labels which are classified into Joy and Netural and Optimism and Upset. we had trained the given dataset by using NLP methods and algorithms.

#### ENVIROMENT USED IS JUPYTER

  

### **Libraries used for the project**

*   pandas
*   numpy
*   matplotlib
*   nltk
*   sklearn
*   genism
*   re
*   svm
*   GaussianNB
*   MultinomialNB
*   DecisionTreeClassifier
*   KNeighborsClassifier
*   RandomForestClassifier
*   LogisticRegression
*   TfidfVectorizer

  

### This application uses the datasets, to find the legitimate emotion for the text given.

1.  Loading dataset
2.  Preprocessing
3.  Word embedding
4.  Training
5.  Testing
6.  Deployment

  

Preprocessing
-------------

#### Preprocessing is crucial in Natural Language Processing (NLP) because it enhances the quality and usability of textual data for machine learning and language analysis tasks. Raw text data often contains various inconsistencies, noise, and irrelevant information that can hinder the accuracy and effectiveness of NLP models.

### Steps done for Preprocesing

*   Tokenization : Break the text into individual words or tokens.
*   Lowercasing : Convert all text to lowercase to ensure consistency in text analysis.
*   Stopword Removal : Eliminate common words (e.g., "the," "and") that don't carry significant meaning.
*   Stemming or Lemmatization : Reduce words to their base or root form (e.g., "running" to "run") to normalize variations.
*   Removing Special Characters and Punctuation: Strip out non-alphanumeric characters and punctuation marks for cleaner text.
*   Removing Extra Whitespace : Remove extra whitespace between words and sentences to clean up the text.
*   Removing Numbers : Remove integers and other numerical characters to clean up the text.

  

### Word Embedding Algorithms

1.  TfidfVectorizer : is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.
2.  Word2Vec : is a popular NLP technique that represents words as dense vector embeddings in a continuous vector space, capturing semantic relationships between words and enabling machine learning models to understand word context and similarities.
3.  GloVe (Global Vectors for Word Representation) : is a word embedding technique in NLP that maps words to dense vectors based on their co-occurrence statistics, capturing semantic relationships and improving the efficiency of natural language understanding tasks.

RESULTS
-------

### DEPLOYED BY USING FLASK

### HOPE YOU UNDERSTAND
