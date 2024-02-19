# Machine-learning-text-analysis-Assignment-HIT

- In this project, the goal is to analyze different texts in Hebrew with the purpose of classifying the gender of every storyteller.

This repository contains code and files related to the Text Analysis assignment. Here's a breakdown of the steps taken to complete the assignment:

**Preceding Step - Import Modules:**

Imported necessary Python modules and packages for data manipulation, visualization, and text analysis.

Used libraries such as Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn.

**Reading Input Files:**

Loaded input files for train annotated corpus and test corpus using Pandas.

Utilized pd.read_csv() function to read CSV files into Pandas DataFrames.

**Tokenization:**

Implemented tokenization methods to preprocess text data.

Created functions to tokenize text by removing English letters, digits, punctuation, and special characters.

Applied tokenization functions to the training and test corpus DataFrames.

**Vectorization:**

Utilized CountVectorizer and TfidfVectorizer for converting text data into numerical feature vectors.

Used these vectorizers to count word occurrences and calculate TF-IDF values for each story in the corpus.

**Cross Validation and Classification:**

Explored various classification models to predict the gender of stories.

Employed models such as LinearSVC, MLPClassifier, Perceptron, SGDClassifier, MultinomialNB, GaussianNB, KNeighborsClassifier, and DecisionTreeClassifier.

Conducted cross-validation to evaluate model performance using F1 score.

Tuned model parameters using GridSearchCV to improve performance.

Save output to CSV.
