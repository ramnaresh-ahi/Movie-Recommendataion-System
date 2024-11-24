# Movie Recommendation System 

This project implements a **Content-Based Movie Recommendation System** that suggests movies based on user preferences. It leverages **Natural Language Processing (NLP)** with NLTK for text processing and Scikit-learn for machine learning.

## 📁 Dataset
- The dataset includes movie titles, genres, descriptions, and other metadata.
- Preprocessed to extract key features relevant for recommendation.

## 🔧 Project Workflow
1. **Data Preprocessing**:
   - Cleaned and normalized text data from movie descriptions.
   - Tokenized and vectorized text using **TF-IDF** to extract meaningful features.
2. **Feature Engineering**:
   - Used text similarity measures (e.g., cosine similarity) to compare movies.
3. **Recommendation System**:
   - Built a content-based filtering model using Scikit-learn to recommend similar movies based on the input preferences.
4. **Evaluation**:
   - Tested the system with various inputs to ensure meaningful and relevant recommendations.

## 🛠️ Tools & Technologies Used
- **Python**: Programming language for development.
- **Libraries**:
  - **NLTK**: For natural language processing (tokenization, stemming, etc.).
  - **Scikit-learn**: For TF-IDF vectorization and similarity computation.
  - **Pandas** and **NumPy**: For data manipulation and preprocessing.
- **Jupyter Notebook**: For interactive development and testing.

## 📊 Key Insights
- Demonstrated the effectiveness of TF-IDF and cosine similarity for content-based recommendations.
- Highlighted the importance of data preprocessing and feature extraction in NLP tasks.

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ramnaresh-ahi/Movie-Recommendation-System.git
