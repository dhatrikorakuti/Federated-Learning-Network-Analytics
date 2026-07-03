[README.md.txt](https://github.com/user-attachments/files/29638161/README.md.txt)
# Federated-Learning-Network-Analytics
Machine Learning project for predicting 5G Network Res Federated Learning-Based Network Resource Allocation Prediction

 Overview

This project predicts 5G network resource allocation 
using Machine Learning and demonstrates a Federated Learning simulation for privacy-preserving decentralized model training.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, 
model training using Random Forest Regression, evaluation, and a simulation of Federated Learning across multiple clients.
-----------

Objectives

- Analyze a 5G Network Resource Allocation dataset.
- Perform data cleaning and exploratory data analysis.
- Train a Random Forest Regression model.
- Evaluate model performance using regression metrics.
- Simulate Federated Learning with multiple clients.

----------------
 Dataset Features

- Application Type
- Signal Strength
- Latency
- Required Bandwidth
- Allocated Bandwidth
- Resource Allocation (Target)
------------------
 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

------------------
Exploratory Data Analysis

The following analyses were performed:

- Correlation Heatmap
- Feature Distributions
- Boxplots
- Scatter Plots
- Application-wise Analysis
- Feature Importance

Sample visualizations are available in the images folder.

-----------

 Machine Learning Model

Algorithm Used:-Random Forest Regression
-------------
Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R² Score

Model Performance
| Metric   | Final Value |
| -------- | ----------: |
| MAE      |  2.3351 |
| RMSE     |  3.3329 |
| R² Score |  0.8620 |


-------------------

Federated Learning Simulation

The dataset was divided into multiple clients.

Each client trained its own local Random Forest model independently.

The local predictions were aggregated to simulate a Federated Learning environment while keeping client data separate.

-------------
 Project Structure


Federated-Learning-Network-Analytics/
│
├── Federated_Learning_5G_Network_Analytics.ipynb
├── 5G_Network_Resource_Allocation.csv
├── README.md
├── requirements.txt
├── images/
└── results/
```

----------------

 Future Improvements

- Implement Flower (FLWR) for real Federated Learning
- Deploy using Streamlit
- Use Deep Learning models
- Train with larger real-world telecom datasets

---

 Author

Dhatri Priya.k

Computer Science Engineering (Data Science)

---

⭐ If you found this project useful, consider giving it a star.ource Allocation with a Federated Learning Simulation
