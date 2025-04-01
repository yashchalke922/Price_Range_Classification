# Price_Range_Classification
## Price Classification Project
Course: NLP (Semester 6) - Pillai College of Engineering

### Project Overview
This project is part of the Natural Language Processing (NLP) course for Semester 6 students at Pillai College of Engineering. The objective of this project is to classify products into predefined price ranges based
on textual descriptions and other relevant features.We leverage various Machine Learning (ML), Deep Learning (DL), and Language Models to analyze product descriptions, extracting meaningful insights that help categorize items into appropriate price bands. The project involves key NLP techniques such as text preprocessing, feature extraction, model training, and evaluation to ensure accurate classification.Through this project, students will gain hands-on experience in working with real-world datasets, applying state-of-the-art models, and optimizing performance for price prediction tasks.
You can learn more about the college by visiting the official website of Pillai College of Engineering.

🔗 You can learn more about the college by visiting the [official website of Pillai College of Engineering](https://www.pce.ac.in).
## Acknowledgements:
We would like to express our sincere gratitude to the following individuals:

Theory Faculty:

1.   Dr.Dhiraj Amin
2.   Dr.Sharvari Govilkar

Lab Faculty:
1. Dr.Dhiraj Amin
2. Dr.Shubhangi Chavan
3. Prof Neha Ashok
Their guidance and support have been invaluable throughout this project.

# *Project Title*: Price Range Classification using Natural Language Processing
The price range classification model processes product descriptions and other relevant textual data to categorize items into predefined price brackets using Natural Language Processing (NLP) and Machine Learning (ML) techniques. By analyzing large volumes of text, the model identifies key features that influence pricing, aiding in better market segmentation and decision-making.The framework consists of text preprocessing (tokenization, stop-word removal, and lemmatization), feature extraction, classification using multiple models, and data collection from various sources. The goal of this project is to enhance product categorization, assist in pricing strategies, and improve user experience in e-commerce and retail applications.

### Algorithms Used:
1. Machine Learning Algorithms:
2. Logistic Regression
3. XGBoost
4. Random Forest
5. SVM
6. KNN

### Deep Learning Algorithms:
1. Convolutional Neural Networks (CNN)
2. BiDirectional Long Short-Term Memory(BiLSTM)
3. Long Short-Term Memory (LSTM)
4. CNN and BiLSTM

### Language Models:
1. RoBERTa
2. BERT 
Comparative Analysis:
The comparative analysis of different models highlights their effectiveness in classifying news articles into the correct category. The following table summarizes the accuracy of the models tested:

## Model Performance Comparison

| Model                                       | Accuracy |
|---------------------------------------------|----------|
| Logistic Regression + Combined Features     | 0.9481   |
| SVM + Combined Features                     | 0.4630   |
| XGBoost on Combined Features                | 0.9667   |
| KNN on Combined Features                    | 0.6259   |
| CNN + Word2Vec                              | 0.9310   |
| LSTM + Word2Vec                             | 0.9113   |
| CNN-BiLSTM + Word2Vec                       | 0.9310   |
| BiLSTM + Word2Vec                           | 0.9359   |
| BERT                                        | 0.9444   |
| RoBERTa                                     | 0.9740   |

### Notes:
- *XGBoost on Combined Features* achieved the highest accuracy (0.9667).
- *Transformer-based models (BERT, RoBERTa)* performed well, but RoBERTa underperformed compared to BERT.
- *Deep learning models using Word2Vec (CNN, LSTM, BiLSTM)* had significantly lower accuracy.
- *Logistic Regression with combined features* performed competitively, suggesting feature engineering played a crucial role.

### Conclusion:
This Price Range Classification project demonstrates the potential of Machine Learning, Deep Learning, and Language Models for text-based classification tasks, particularly in categorizing products into appropriate price ranges. The comparative analysis reveals that XGBoost, a machine learning-based model, outperforms transformer-based methods and deep learning models in terms of accuracy.By employing various algorithms, we gain insights into the strengths and weaknesses of each model, allowing us to choose the most effective approach for automated price classification. The study highlights the importance of feature engineering, model selection, and NLP techniques in improving classification accuracy.

This project serves as a valuable learning experience, demonstrating real-world applications of NLP and classification models in e-commerce, retail, and pricing strategies.
