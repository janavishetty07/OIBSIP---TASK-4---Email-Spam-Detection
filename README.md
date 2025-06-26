
 
 Email Spam Detection 

This project was developed as part of my Data Science internship and focuses on building a machine learning model to detect spam messages. The main objective is to classify SMS messages as either spam or ham (not spam) using machine learning and Natural Language Processing (NLP) techniques.

🧰 Tools & Technologies Used

  Python– Programming language used for development
  Pandas & NumPy – For data manipulation and numerical operations
  NLTK – For text preprocessing like stopword removal and stemming
  Scikit-learn– For machine learning models, evaluation metrics, and vectorization
  Matplotlib & Seaborn – For visualizing data and results
  Pickle – For saving trained models to reuse them later.

 Project Workflow

1. Data Loading and Exploration
   The SMS dataset was loaded and explored to understand its structure and contents. Null values and irrelevant columns were removed.

2. Text Preprocessing
   Each message was cleaned by removing special characters, converting to lowercase, removing stopwords, and stemming words using NLTK. This resulted in a clean corpus of text data.

3. Feature Extraction
   The cleaned text was transformed into numerical format using CountVectorizer, which created a bag-of-words representation of the messages.

4. Label Encoding
   The target column (labels: spam/ham) was encoded into binary values using one-hot encoding, with 1 representing spam and 0 representing ham.

5. Train-Test Split
   The dataset was split into training and testing sets in an 80:20 ratio to evaluate model performance.

6. Model Training
   Three different machine learning models were trained on the training data:

   * Random Forest Classifier
   * Decision Tree Classifier
   * Multinomial Naïve Bayes

7. Model Evaluation
   The models were evaluated using accuracy scores, confusion matrices, and classification reports. Visualizations like heatmaps were used to interpret the results.

8. Model Saving
   The trained models were saved as `.pkl` files using the Pickle library. These models can be used later without the need to retrain.

 📁 Project Contents

* Cleaned and processed dataset
* Jupyter Notebook with step-by-step code implementation
* Trained model files (`RFC.pkl`, `DTC.pkl`, `MNB.pkl`)
* Visualizations and evaluation reports (accuracy, confusion matrix, classification metrics)


✅ Conclusion

This project shows how machine learning can be applied to a practical task like spam detection. Using natural language processing and classification models, I was able to build a system that accurately identifies spam messages.

Among all the models tested, Multinomial Naïve Bayes gave the best performance for this kind of text classification problem. This project helped me understand key concepts like text preprocessing, model training, evaluation, and deployment using Pickle.

It was a valuable part of my Data Science internship, where I learned how to apply theory to real-world problems and gained hands-on experience with essential tools and libraries.


