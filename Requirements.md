# Prerequisites
__Ensure you have the following Python packages installed:__ <br>

     pip install numpy pandas matplotlib seaborn nltk scikit-learn

---
The required Python packages are:
- __numpy:__ For numerical operations.
- __pandas:__ For data manipulation and analysis.
- __matplotlib:__ For plotting and data visualization.
- __seaborn:__ For advanced data visualizations.
- __nltk:__ For natural language processing tasks, such as stopword removal and text lemmatization.
- __scikit-learn (sklearn):__
                              - __TfidfVectorizer:__ For converting text into numerical features.
                              - __cross_val_score, train_test_split:__ For model evaluation and splitting data.
                              - __MultinomialNB:__ For building the Naive Bayes classification model.
                              - __DecisionTreeClassifier: For building the decision tree model.
                              - __classification_report, confusion_matrix, accuracy_score: For evaluating model performance.
- __re: For regular expression operations to clean the text data.
- __string: For string manipulation.
- __warnings: For filtering out warnings during execution.
- Additionally, ensure the NLTK data for stopwords and WordNet lemmatizer is downloaded: <br>


           - import nltk
           - nltk.download("stopwords")
           - nltk.download("wordnet")
