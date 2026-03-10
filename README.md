# Customer-Review-Sentiment-Analysis
#### Summary
Built a supervised NLP pipeline using Python, Pandas, and scikit-learn with Count and TF-IDF vectorisation, benchmarking Logistic Regression, Linear SVC, and Multinomial Naive Bayes models to achieve a 0.899 F1 score with unigram TF-IDF and Linear SVC model.

#### Problem Statement
This project explores whether Amazon Toy & Games review text can reliably predict customer sentiment using a 20,000-review sample drawn from a much larger dataset spanning 1996 to 2023. The goal is to determine whether text-based sentiment analysis can help identify misleading star ratings and uncover hidden customer dissatisfaction that may otherwise lead to trust erosion, churn, and missed product issues.

## Original Project Requirements
For this mini-project you will apply predictive modelling on an area of your choice.
Choose a dataset (at least a few hundred rows) or select a question and
identify and gather the data you need. Follow the steps presented in the
course so far:

a) Perform EDA on the data
b) Select the outcome/response variable
c) Select features (optionally perform feature engineering)
d) Select approaches/models (at least a few)
e) Apply the models and evaluate them

Present from slides in 8-12 minutes.
  
The Jupyter notebooks should be readable and well-commented.

# TO BE EDITTED
## Data Set: Doctor’s Handwritten Prescription BD dataset
[Amazon Reviews 2023 - Toys & Games dataset](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023)

## Exploratory Data Analysis
-  **Data Distribution**: A Data distribution was performed reviewing number of reviews from unique userIDs, Parent ASIN & By Star Rating.
-  **Shape, Info, Describe**: Basic evaulation was performed to understand the number of classes and available data in each column. Also identifying any null, NA or missing values.
-  **Distribution Visualisation & Analysis**: Distribution Analysis was further performed on Helpful votes, Total reviews by year, and share of raitings. Text standard analysis using text stat, world cloud post text processing was also performed.

## Text Preprocessing
Preprocesing was performed on text using a manual method and spacy. Steps taken.

- Expand contractions
- Removed html tags with Beautiful soup
- Removed Emoticons, symbols, pictographs, flags, dingbats via Unicode
- Normalise case
- Removed hyphens, spaces, digits, non-ASCII characters
- Removed text related to star raiting to prevent data leakage.

## Modelling
Utilised Count and TF-IDF Unigram vectorisation combined with supervised classification models Logistic Regression, Linear SVC, and Multinomial Naive Bayes to find most optimal model for sentiment analysis using ML.

## Project Documents
**Jupyter Notebook** - [01-Amazon-Sentiment-analysis-Mini-Project-3.ipynb](./01-Amazon-Sentiment-analysis-Mini-Project-3.ipynb) \

**Powerpoint Presentation Slides** - [Presentation-Amazon-Sentiment-analysis-Mini-Project-3](./Presentation-Amazon-Sentiment-analysis-Mini-Project-3) \
