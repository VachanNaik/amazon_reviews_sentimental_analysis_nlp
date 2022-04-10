# amazon_reviews_sentimental_analysis_nlp

**Business Problem.** Your task is to *build models which can identify the sentiment (positive or negative) of each of these non-rated interactions*.

**Analytical Context.** The data is a set of reviews in CSV file format. We will combine some text processing procedures  and classification models to develop algorithms capable of classifying interactions by sentiment.

Will be doing the following in this case:
1. Read and analyze the input text data and the corresponding response variables (ratings)
2. Perform basic pre-processing to prepare the data for modeling
3. Learn and apply various ways of featurizing the reviews text
4. Build machine learning models to classify text as either exhibiting positive or negative sentiment (1 or 0).

Text visualization using word clouds (word clouds )
As visualization is crucial for numerical data, it is also important for text data. However, the text does not lend itself to histogram charts or scatterplots, as numerical data does. In such cases, the word clouds are a common and very useful tool to appreciate the text distribution.

Text preprocessing and normalization is crucial before building a proper NLP model. Some of the important steps are:

1. Converting words to lower/upper case
2. Removing special characters
3. Removing stopwords and high/low-frequency words
4. Stemming/lemmatization

Building machine learning model on the pre-proceesed text data, by implimemting regression and TFIDF method to calculating the best accuracy.
