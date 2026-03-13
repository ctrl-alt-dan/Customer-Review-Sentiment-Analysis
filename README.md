# Customer-Review-Sentiment-Analysis
#### Summary
Built a supervised NLP pipeline using Python, Pandas, and scikit-learn with Count and TF-IDF vectorisation, benchmarking Logistic Regression, Linear SVC, and Multinomial Naive Bayes models to achieve a 0.899 F1 score with unigram TF-IDF and Linear SVC model.

#### Problem Statement
This project explores whether Amazon Toy & Games review text can reliably predict customer sentiment using a 20,000-review sample drawn from a much larger dataset spanning 1996 to 2023. The goal is to determine whether text-based sentiment analysis can help identify misleading star ratings and uncover hidden customer dissatisfaction that may otherwise lead to trust erosion, churn, and missed product issues.

## Original Project Requirements
Choose a dataset for a text classification task – such data might be obtained via web scraping or may already
exist in clean form. There needs to be a target variable containing the category of text. \
\
Carry out the following steps.
a) Perform tokenisation and remove stop words.
b) Apply stemming and/or lemmatisation (optional).
c) Perform EDA on the text (e.g. bar charts, word clouds)
d) Create features such as word counts, parts of speech, vectorisation (e.g. Word2Vec, TF-IDF).
e) Select and apply two or more predictive models to predict the category of text.
f) Evaluate the models and present your findings.

Present from slides in 8-12 minutes.
  
The Jupyter notebooks should be readable and well-commented.
## Data Set
[Amazon Reviews 2023 - Toys & Games dataset](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023)

## Exploratory Data Analysis
- **Shape, Info, Describe**: Inspection of dataset size, column structure, and potential missing values.
- **Text Length Analysis**: Distribution analysis of review length and word counts.
- **Sentiment Distribution**: Examination of class balance between positive and negative sentiment.
- **Word Frequency Analysis**: Identification of commonly occurring terms within the review corpus.
- **Data Quality Checks**: Detection of duplicates, empty reviews, and anomalies within the text data.

## Text Preprocessing
Text preprocessing was performed to convert raw customer reviews into structured features suitable for machine learning models.

Steps included:
- Lowercasing text
-	Removal of punctuation and special characters
- Tokenisation
- Stop word removal
- Vectorisation using CountVectorizer
- Feature generation using TF-IDF

These transformations converted unstructured text into numerical representations suitable for model training.

## Modelling
Multiple machine learning models were trained and evaluated to classify review sentiment.

Models explored include:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

The modelling process included:
- Training and validation splits
- Feature representation comparison (Count vs TF-IDF)
- Performance evaluation using accuracy, precision, recall, and Macro F1
- Model comparison to identify the most effective classifier

## Project Documents
**Jupyter Notebook** - [01-Amazon-Sentiment-analysis-Mini-Project-3.ipynb](./01-Amazon-Sentiment-analysis-Mini-Project-3.ipynb) \

**Powerpoint Presentation Slides** - [Presentation-Amazon-Sentiment-analysis-Mini-Project-3](./Presentation-Amazon-Sentiment-analysis-Mini-Project-3) \
