# TED Talks Recommendation System Using Machine Learning
### 📌  Overview
This project aims to build a TED Talks Recommendation System that suggests talks based on user input using content-based filtering. It leverages Natural Language Processing (NLP) techniques and cosine similarity to recommend similar TED talks, enhancing user experience by helping them discover talks aligned with their interests.

### 🎯 Objective
To recommend TED Talks based on a topic or a talk entered by the user.
To implement a machine learning model that suggests similar content using text-based similarity.
To enhance the discoverability of meaningful and relevant TED content.

# Tools & Technologies Used
### Language: Python
### .Libraries:

.Pandas

.NumPy

.Matplotlib

.Seaborn

.NLTK (Natural Language Toolkit)

.Scikit-learn (for TF-IDF Vectorizer & Cosine Similarity)

.WordCloud (for visualization)

# Dataset
### Source: TED Talks Dataset (2006–2020)

### Features Used:

.Title

.Description

.Speaker

.Event

.Duration

.Ratings

.Tags

# Methodology
### 1. Data Preprocessing
Removed duplicates and null values.

Cleaned text data (e.g., lowercasing, removing punctuation, stop words).

Merged relevant features (title, description, tags) into a single text field.

### 2. Text Vectorization
Used TF-IDF Vectorizer to convert text data into numerical form.

### 3. Similarity Calculation
Applied Cosine Similarity to compute the similarity between different TED Talks.

### 4. Recommendation System
Input: A keyword, title, or short description.

Output: A list of top N similar TED Talks based on content.

# Results
Implemented a working content-based recommendation system.

Achieved relevant recommendations for a variety of input topics.

Visualized most common tags using a WordCloud.

# Visualizations
WordCloud of most frequent words in TED Talk descriptions.

Bar plots showing distribution of talk durations and categories.







