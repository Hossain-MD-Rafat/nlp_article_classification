# **News Article Classification**

## **Overview**
This project focuses on classifying news articles into predefined categories using machine learning and transformer-based models. It includes data preprocessing, exploratory data analysis (EDA), and model training with **sentence transformers** and a **Random Forest classifier**.

## **Features**
- **Data Preprocessing**: Handling missing values, text cleaning, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Understanding dataset distribution and category insights.
- **Machine Learning Model**: Sentence embedding with **sentence transformers** and classification using **Random Forest**.
- **Deep Learning Model**: Using **T5 Transformer** for text classification.
- **Evaluation Metrics**: Accuracy, precision, recall, F1-score, and confusion matrix.

## **Dataset**
The dataset consists of the following key columns:
- **Article**: The text content of the news article.
- **Category**: The label corresponding to the article's category (e.g., World, Sports, Business, Sci/Tech).

**Recommended Environment:**  
- Google Colab (with GPU enabled)  
- Python 3.8+  
- Torch & TensorFlow  

## **Project Workflow**
1. **Load & Explore the Dataset**: Read the dataset and check for missing values or imbalances.
2. **Feature Engineering**: Encode text using **sentence transformers**.
3. **Model Training**: Train different models, including:
   - Random Forest (baseline & tuned versions)
   - Transformer-based models (T5)
4. **Evaluation & Analysis**: Compare performance metrics and generate insights.
5. **Final Submission**: Document findings and save results.
