# Disaster Tweet Classification using LSTM 🌍🔍

## Introduction ℹ️
In this project, we developed a deep learning model using Long Short-Term Memory (LSTM) networks to classify tweets into two categories: disaster-related and non-disaster-related. This classification is crucial for emergency response, public safety, and disaster management applications. We applied Natural Language Processing (NLP) techniques and deep learning to achieve this classification.

## Data Preparation 🛠️
We started by loading the datasets containing tweet information. The data underwent several preprocessing steps, including handling missing values, text cleaning, and combining text with keyword and location information. Text data was tokenized, padded, and handled class imbalance using Synthetic Minority Over-sampling Technique (SMOTE). The preprocessed data was split into training and validation sets for model training.

## Model Architecture 🧠
We built an LSTM neural network model for tweet classification. The model consisted of an embedding layer, a bidirectional LSTM layer, and a dense output layer with sigmoid activation. The model was compiled using the Adam optimizer and binary cross-entropy loss function.

## Model Training and Evaluation 🏋️‍♂️
The model was trained for 15 epochs with a batch size of 32. We visualized the accuracy and loss on both training and validation sets to monitor the model's performance over epochs. We evaluated the model's performance using the F1 score, a metric that considers both precision and recall. The F1 score on the validation data was approximately 0.74, indicating a good balance between precision and recall.

## Advanced Exploratory Data Analysis (EDA) and Visualizations 📊
We performed advanced EDA to gain insights into the tweet data. Word clouds were generated for disaster and non-disaster tweets, showcasing the most common words in each category. We also visualized the tweet length distribution for both categories and explored the most common keywords in disaster and non-disaster tweets.

## Model Performance Visualization 📈
We visualized the training and validation accuracy and loss over epochs to analyze the model's learning process. Additionally, we created a confusion matrix heatmap to visualize the model's performance in detail.

## Conclusion 🎉
This project demonstrated the application of deep learning techniques for classifying disaster-related tweets. The developed LSTM model showed good performance in distinguishing between disaster and non-disaster tweets. The insights gained from advanced EDA further enhanced our understanding of the tweet data, contributing to the overall analysis.

Feel free to explore the provided code and visualize the results! 🚀

Follow me on LinkedIn: [Vidhi Waghela](https://www.linkedin.com/in/vidhi-waghela-434663198/) \\
Kaggle: [Vidhi Kishor Waghela](https://www.kaggle.com/vidhikishorwaghela) \\
GitHub: [Vidhi1290](https://github.com/Vidhi1290)
