# **Email Spam Detection Project**

## **Project Overview**
This project demonstrates the use of **Machine Learning** and **Natural Language Processing (NLP)** to detect spam emails. The model uses the **Multinomial Naive Bayes** algorithm to classify emails as **spam** or **ham** based on a labeled dataset.

---

## **Technologies Used**
- **Python**: Programming language
- **Libraries**:
  - **Pandas**: Data loading and manipulation
  - **NLTK**: Text preprocessing (stopword removal, text cleaning)
  - **Scikit-learn**: Machine learning (Multinomial Naive Bayes) and model evaluation
  - **Matplotlib/Seaborn**: Data visualization (confusion matrix)
- **Google Colab**: Cloud-based environment for running the project
- **Google Drive**: Dataset storage
- **Dataset**: Labeled email dataset in CSV format for spam detection

---

## **Project Features**
- **Data Preprocessing**: Cleans and prepares the email dataset for analysis (removes special characters, stopwords, etc.).
- **Feature Extraction**: Converts raw text data into numerical format using **TF-IDF**.
- **Model Training**: Trains a **Multinomial Naive Bayes** classifier to predict whether an email is spam or ham.
- **Model Evaluation**: Provides accuracy, precision, recall, and confusion matrix to evaluate the model's performance.
- **Visualization**: Confusion matrix heatmap for easy interpretation of model results.

---
## **Usage**
1. Open the project in **Google Colab**.
2. Mount your Google Drive and upload the **spam.csv** dataset.
3. Run the notebook cells to preprocess the data, train the model, and evaluate the performance.
4. Test the model on sample email data to classify it as **spam** or **ham**.

---

## **Results**
- The model provides a classification accuracy along with a detailed **classification report**.
- A **confusion matrix** is visualized to assess the true positive, false positive, true negative, and false negative predictions.

---

## **Contributing**
Feel free to fork this project and make improvements or modifications. If you have suggestions or find bugs, open an issue or submit a pull request.

---

## **License**
This project is licensed under the MIT License.

