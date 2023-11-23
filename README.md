# Consumer Review Summarization

## Project Overview
My goal for this project is to create a model that summarizes reviews which will enable customers to quickly skim through reviews when evaluating a product. This system will condense the content of a review and its associated rating into a single-line comment, categorized as positive, neutral, or negative based on the rating given.

## Part One
In the initial step of this customer review summarization project, the focus is on the analysis of customer feedback. The primary goal is to dissect, understand, and represent the data visually. Many python libraries are used to inspect the text data with the goal of gaining understanding that can potentially enhance customer service.

### Installation
Before starting with the analysis, ensure the following Python libraries are installed or imported:

- `pandas`: For data manipulation and analysis.
- `collections`: Specifically, `Counter` from this library is used for tallying hashable objects.
- `nltk`: This is the Natural Language Toolkit, essential for processing textual data. After the initial installation of `nltk`, you may need to download additional resources, such as tokenizers and the stopwords corpus, to fully utilize its capabilities for text analysis.
- `matplotlib`: A plotting library for creating static, interactive, and animated visualizations in Python.
- `seaborn`: A Python data visualization library based on matplotlib that provides a high-level interface for drawing attractive statistical graphics.

## Part Two
For part 2 of this project I develop a baseline model utilizing a Naive Bayes classifier to summarize customer reviews efficiently. The system is designed to extract the essential information and rating from each review and condense them into a summarized review. These summaries will be labeled as positive, neutral, or negative to match the rating of the review. The effectiveness of the model is be evaluated by its accuracy and log loss metrics to guarantee the dependability of the summaries and the accuracy of the sentiment classification.


### Installation
To achieve this summarization, the following Python libraries and methods are employed:

- `pandas` for data manipulation and analysis.
- `numpy` for numerical operations.
- `matplotlib.pyplot` for visualizing the data.
- `string` for standard string operations.
- `random` for generating random numbers.
- `nltk.corpus` for stopword library.
- `nltk.tokenize` for tokenizing text into sentences and words.
- `sklearn.feature_extraction.text` for converting text data into TF-IDF vectors.
- `sklearn.model_selection` for splitting datasets and cross-validating parameters.
- `sklearn.naive_bayes` for implementing the Naive Bayes algorithm.
- `nltk.probability` for frequency distribution of words.
- `heapq` for finding the largest values in datasets.
- `sklearn.metrics` for evaluating the accuracy and log loss of the model.
- `sklearn.preprocessing` for encoding labels.
- `wordcloud` for visual representation of text data.
- `FreqDist` for the frequency distribution of words.

## Part Three
Pre-trained deep learning model (t5-small)


### Installation




