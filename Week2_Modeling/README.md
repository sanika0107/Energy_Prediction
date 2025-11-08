# ⚙️ Week 2 – Model Training & Accuracy (Plant 1)

This week focuses on building and evaluating a **Machine Learning model** for predicting solar energy output (DC Power) using the preprocessed Plant 1 dataset.

## 🎯 Objective
To train a regression model that predicts solar power generation based on weather parameters such as ambient temperature, module temperature, and irradiation.

## 🧠 Tasks Performed
1. Loaded the **cleaned dataset** from Week 1 (`Plant_1_Preprocessed.csv`)
2. Selected key input features:
   - Ambient Temperature  
   - Module Temperature  
   - Irradiation
3. Set the target variable as **DC Power**
4. Split the data into **training (80%)** and **testing (20%)**
5. Trained a **Linear Regression** model
6. Predicted the power output for test data
7. Compared **actual vs predicted** values
8. Evaluated the model using:
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score (Model Accuracy)

## 📊 Results
- The model successfully learned the relationship between weather and power output.  
- R² score (accuracy) indicates how well the model predicts solar energy generation.  
- Scatter plots were used to visually compare **actual vs predicted** DC Power values.
- 
## 🛠️ Tools & Libraries
- **Python 3.12**
- **Google Colab**
- **pandas**, **numpy**
- **scikit-learn**
- **matplotlib**, **seaborn**

## 📁 Files in This Folder
| File | Description |
|------|--------------|
| `Plant_1_Solar_Prediction_Model_Week2.ipynb` | Colab notebook for training and evaluating the ML model |
| `README.md` | Documentation for Week 2 activities |

## 🚀 Next Steps
- Implement advanced models like **Random Forest** or **Gradient Boosting**  
- Compare their accuracy with Linear Regression  
- Visualize performance metrics and feature importance
