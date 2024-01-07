<h1 align="center" id="title">Shopalyics</h1>

<p align="center"><img src="https://socialify.git.ci/navyadua/Shopalytics/image?name=1&amp;pattern=Signal&amp;theme=Light" alt="project-image"></p>

<p align="center"><img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&amp;logo=Python&amp;logoColor=white" alt="shields"><img src="https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&amp;logo=Google-Colab&amp;logoColor=white" alt="shields"><img src="https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&amp;logo=scikit-learn&amp;logoColor=white" alt="shields"><img src="https://img.shields.io/badge/NLTK-017478.svg?style=for-the-badge&amp;logo=Python&amp;logoColor=white" alt="shields"></p>


## Introduction 🌟

Welcome to Shopalytics - an end-to-end project that involves scraping data from an online marketplace and detecting fake reviews using machine learning techniques. This project aims to extract valuable insights from product data and identify potentially deceptive reviews among them.

## Project Overview 🌟

### Features
### Web Scraping 🕸️
The web scraping component involves using tools like Beautiful Soup and Selenium to extract specific information from web pages. In this project, it focuses on an online marketplace to gather product details such as names, descriptions, prices, and ratings. Beautiful Soup is utilized for parsing HTML content and extracting structured data, while Selenium is employed for tasks requiring interaction with JavaScript elements or dynamic web content.

### Data Cleaning 🧹
Data cleaning is crucial for preparing raw data for analysis. This phase involves handling missing or null values, text preprocessing (e.g., removing special characters, lowercasing text), and feature engineering. Techniques like TF-IDF (Term Frequency-Inverse Document Frequency) are applied to transform text data into numerical representations, enabling machine learning algorithms to work effectively.

### Sentiment Analysis 📝
Sentiment analysis involves determining the sentiment or emotional tone within textual data. NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner) tool is utilized for sentiment analysis. VADER assigns sentiment scores to reviews, classifying them as positive, negative, or neutral based on lexicon and rule-based analysis. This aids in understanding the overall sentiment distribution and helps in detecting potentially biased or misleading reviews.

### Similar Product Identification 🔍
Similar product identification is a process to find products that share similarities based on their names or descriptions. TF-IDF, in combination with cosine similarity, measures the similarity between products by analyzing the frequency of words across different product names or descriptions. This approach allows for the identification of related or similar products, aiding in grouping or recommendation systems.

### Fake Review Detection 🕵️‍♂️
Fake review detection involves employing machine learning algorithms, particularly K-Means clustering, to identify patterns among reviews. This approach leverages TF-IDF representation, sentiment analysis scores, and review ratings to cluster reviews. By detecting anomalies or clusters with distinct characteristics, such as conflicting sentiment scores with review ratings, the model can potentially flag or separate out suspicious or fake reviews.

### Evaluation 📊
The evaluation phase assesses the performance of the fake review detection model. Metrics like Silhouette, Calinski-Harabasz, and Davies-Bouldin scores are used to evaluate the quality of clustering. These metrics measure the compactness of clusters and the separation between clusters, providing insights into how well the K-Means algorithm has grouped the reviews.

## Usage 🚀

### Installation and Requirements 🛠️
- Python 3
- Libraries Used:
  - Beautiful Soup
  - Selenium
  - Pandas
  - NumPy
  - Scikit-learn
  - NLTK
  - Matplotlib

### Running the Notebook 📓
- Open the `Shopalytics.ipynb` file in Jupyter Notebook or JupyterLab.
- Execute cells in sequential order to run the entire code.
- Each section is clearly marked with headings and comments for better understanding.

# Contributors ![image](https://user-images.githubusercontent.com/91384754/225902068-ccb9f7ff-2f90-4f49-b307-0695951f03a8.png)

[Navya Dua](https://github.com/navyadua)

[Meghana Joseph](https://github.com/MeghanaJo)


This project consolidates the entire process, from data collection through web scraping to the identification of fake reviews using machine learning techniques. Each step is documented and includes explanations and comments for clarity.

Thank You for checking out our project!😉 We believe in creating a better world through technology⚙️, and we hope this project contributes to that goal.👍🏻

# 
