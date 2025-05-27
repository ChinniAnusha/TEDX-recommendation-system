# TEDX-recommendation-system
Project Overview
This project focuses on developing a basic recommendation system that suggests TED Talks to users based on their topics of interest. By leveraging machine learning techniques, the system aims to provide personalized content recommendations, enhancing user engagement and experience.
 Approach
1. Data Collection & Preprocessing
Dataset: The dataset comprises TED Talks from 2006 to 2020, including details like the speaker's name, talk title, and more.
Data Cleaning: Unnecessary columns are removed, and missing values are handled appropriately.
Feature Engineering: New features such as the year and month of the talk are extracted from existing data.
Text Consolidation: The 'title' and 'details' fields are combined to create a comprehensive text field for analysis.
 Approach
2. Text Processing
Libraries Used: NLTK for natural language processing tasks.
Stop Words Removal: Commonly used words that do not contribute to the meaning are removed.
TF-IDF Vectorization: The text data is converted into numerical form using Term Frequency-Inverse Document Frequency (TF-IDF) to reflect the importance of words.
3. Similarity Computation
Cosine Similarity: This metric is used to measure the similarity between different TED Talks based on their TF-IDF vectors.
4. Recommendation Generation
User Input: The system takes a topic of interest as input from the user.
Recommendation: Based on the input, the system identifies and recommends TED Talks that are most similar in content.
Outcomes
Functional Recommender System: Successfully built a basic content-based recommendation system for TED Talks.
User Engagement: Enhanced the ability for users to discover talks aligned with their interests.
Scalability: The approach can be extended to incorporate more sophisticated recommendation techniques in the future.
Technologies & Tools
Programming Language: Python
Libraries:
Pandas & NumPy for data manipulation
Matplotlib & WordCloud for data visualization
NLTK for text processing
Scikit-learn for machine learning tasks
