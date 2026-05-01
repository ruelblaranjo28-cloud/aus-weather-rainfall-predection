# 🌦️ Australia Weather Rainfall Prediction

Machine Learning project that predicts whether it will rain the next day using historical Australian weather data.

## 🚀 Built using Python, Scikit-learn, and data visualization techniques.

---

## 📌 Project Overview

This project builds a classification model to predict rainfall (Yes/No) based on weather features such as humidity, pressure, temperature, and wind conditions.

The goal is to explore machine learning techniques and evaluate model performance in a real-world dataset.

---

## 🤖 Models Implemented

- Logistic Regression
- Random Forest Classifier

Both models were trained and evaluated to compare their effectiveness in predicting rainfall.

---

## 📊 Model Performance

- Overall Accuracy: ~84%
- Strong performance in predicting No Rain
- Lower recall for Rain, indicating difficulty detecting minority class

---

## 📈 Key Insights

- Humidity (3pm) and Pressure (3pm & 9am) are the most important predictors
- The dataset is imbalanced, affecting prediction of rain events
- Improving recall for rain could be achieved using:
  - SMOTE / resampling techniques
  - Threshold tuning
  - Advanced ensemble models

---

## 📊 Visual Results

Confusion Matrix

"Confusion Matrix" (Australia_Outputs/confusion_matrix.png)

Feature Importance

"Feature Importance" (Australia_Outputs/aus_weather_feature_importance.png)

Rainfall Feature Importance

"Rainfall Feature Importance" (Australia_Outputs/aus_weather_rainfall_feature_importance.png)

---

## 🧰 Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 📁 Project Structure

- "FinalProject_AUSWeather.ipynb" → Main notebook
- "Australia_Outputs/" → Model visualizations and outputs

---

## 🚀 Future Improvements

- Apply SMOTE or resampling techniques
- Hyperparameter tuning (GridSearchCV)
- Try advanced models (XGBoost, Gradient Boosting)

---

## 💡 Why This Project Matters

Accurate rainfall prediction is important for agriculture, disaster prevention, and daily planning.
This project demonstrates how machine learning can support real-world decision-making.

---

## 👨‍💻 Author

### Ruel Laranjo
Aspiring Data Scientist | Machine Learning Enthusiast
📍 Philippines
🔗 Open to Data Analyst / Junior Data Scientist roles

---
