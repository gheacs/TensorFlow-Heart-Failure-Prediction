# Heart Failure Prediction

## Project Overview
Cardiovascular diseases (CVDs) stand as the leading cause of death globally, claiming approximately 17.9 million lives each year, which represents 31% of all global deaths. Among these, heart failure is a prevalent event, often resulting from various CVDs. This project aims to utilize machine learning to predict mortality due to heart failure, leveraging a dataset that encapsulates critical clinical features.

## Dataset Description
The dataset, sourced from Kaggle, encompasses 12 features that are instrumental in forecasting heart failure mortality. These features include:
1. Age
2 Anaemia
3. Serum creatinine
4. Ejection fraction
5. Diabetes
6. High blood pressure
7. And other relevant clinical parameters
These attributes are crucial in assessing the likelihood of survival for patients suffering from heart failure.

## Objective
The primary goal of this project is to develop a machine learning model that can accurately predict the survival chances of heart failure patients based on their clinical data, thus aiding in early detection and proactive management of cardiovascular risk factors.

## Installation
To set up the project environment, follow these steps:

```bash
git clone https://your-repo-link-here.git
cd your-project-directory
pip install -r requirements.txt
```

## Usage
To run the prediction model:
```bash
python app.py
```

## Model and Analysis
- Framework: TensorFlow's Keras API.
- Architecture:
    Input Layer: Matches the number of features in the dataset.
    Hidden Layers: Dense layers with ReLU activation.
    Output Layer: Dense layer with softmax activation for categorical output.
- Compilation: The model uses categorical_crossentropy for loss, adam as the optimizer, and evaluates accuracy

## Insights and findings from the analysis.
1 The model performs better in identifying class 0 than class 1, as evidenced by higher recall and F1-score for class 0.  
2. The precision is similar for both classes, indicating a balanced performance in terms of positive prediction accuracy.  
3. The overall accuracy of 0.68 suggests that the model correctly predicts the class 68% of the time across the entire dataset.  
4. The macro and weighted averages provide a holistic view of the model's performance across the classes.  


