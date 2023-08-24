# Natural-Language-Processing-for-Fake-News-Detection
GOAL

To predict whether news provided is real or fake

DATASET

The Fake News Dataset is from Kaggle https://www.kaggle.com/competitions/fake-news/overview

DESCRIPTION

The project mainly focuses on handling huge amounts of text data, extracting meaningful information from it using methods like lemmatization, stemming, tokenization and soo much more and then passing all these informations as features to a model and making a prediction whether the news is reliable(0) or unreliable(1)

WHAT I HAD DONE

The very first step is doing an exploratory data analysis, in which I explored the relationship between labels and features
Compared the data before and after preprocessing, significantly reduced less informative data like punctuations and stopwords For preprocessing I have used methods like
Lower casing
Removed stopwords,puntuations
Performed Stemming (Finding root words like for functioning root word will be function) using nltk's PorterStemmer
Created sparse matrix using CountVectorizer for vocab size of 6000 features using bag of words and n-grams to extract more details
Train/Test Validation splits Finally trained models, tuned them to make final predictions

MODELS USED

I have used these models as they perform good classification of text data

Decision Tree Classifier
Random Forest Classifier
XGBClassifier
Naive Bayes- MultinomialNB
Out of these models I choose Random Forest Classifier as it performed good and handle larges streams of text data very well

LIBRARIES NEEDED

scikit-learn
nltk
matplotlib
seaborn
pandas
numpy
Results
Accuracy_score for Random Forest : 93.9 %
Accuracy_score for SVM : 93.3 %
Accuracy_score for Decision Tree: 92 %
Accuracy_score for XGBoost : 92.58 %
Accuracy_score for MultinomialNB : 86.79 %
Random Forest algorithm performing very Well compared to other with accuracy ~ 94 %
