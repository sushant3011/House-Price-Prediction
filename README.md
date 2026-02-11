🏡 House Price Prediction using Machine Learning

A Machine Learning project that predicts house prices based on various housing features using regression techniques. This project demonstrates data preprocessing, model training, pipeline creation, and model deployment using saved pickle files.


📌 Project Overview

This project uses a housing dataset (housing.csv) to train a regression model capable of estimating house prices. It includes:

- Data preprocessing

- Feature engineering

- Model training

- Model & pipeline serialization

- Price prediction using saved model

The trained model and preprocessing pipeline are saved as model.pkl and pipeline.pkl for reuse without retraining.

📂 Project Structure
House-Price-Prediction/
```
House-Price-Prediction/
│
├── housing.csv          # Dataset used for training
├── model.pkl            # Trained regression model
├── pipeline.pkl         # Preprocessing pipeline
├── main.py              # Main prediction script
├── main2.py             # Alternate/extended script
├── .gitignore
├── .gitattributes
└── README.md
```

🧠 Features

- ✔ Data loading and cleaning  
- ✔ Handling missing values  
- ✔ Feature scaling and transformation  
- ✔ Categorical variable encoding  
- ✔ Regression model training  
- ✔ Model serialization using pickle  
- ✔ Prediction on new data

🛠️ Technologies Used

- Python

- Pandas – Data manipulation

- NumPy – Numerical operations

- Scikit-learn – Machine Learning

- Pickle – Model saving & loading

  📊 Dataset

The dataset (housing.csv) contains housing information such as:

- Area / Size

- Number of bedrooms

- Location or categorical features

- Other numerical attributes

- Target variable: House Price

The model learns relationships between these features and the house price
