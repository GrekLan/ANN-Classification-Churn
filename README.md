Built an interactive customer churn prediction web application using Streamlit and a pre-trained TensorFlow neural network model. The app allows business stakeholders to input customer profile details and receive a real-time prediction of churn probability.

Key features include:

A user-friendly interface to input features such as geography, gender, age, balance, credit score, and more.

Data preprocessing with custom-trained encoders (LabelEncoder, OneHotEncoder) and StandardScaler to match the original model training pipeline.

Geographic one-hot encoding and gender label encoding handled dynamically with pre-loaded pickled encoders.

Integrated churn probability output based on thresholding, with clear business insights (likely to churn / not likely to churn).
