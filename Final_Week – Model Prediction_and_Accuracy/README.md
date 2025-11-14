# ⚙️ Final Week – Model Training, Prediction & Accuracy (Plant 1)

This week focuses on **training a machine learning model** to predict solar energy output (DC Power) using the preprocessed Plant 1 dataset.  
Visualizations of **AC and DC Power** trends are also included to understand generation patterns.

---

## 🎯 Objectives
- Split the dataset into training and testing sets  
- Train a **Linear Regression** model  
- Predict solar energy output (DC Power)  
- Compare predicted values with actual values  
- Plot AC and DC power graphs and check accuracy  

---

## 🧠 Tasks Performed
1. Loaded the cleaned dataset (`Plant_1_Preprocessed.csv`)  
2. Converted timestamps to proper datetime format  
3. Visualized:
   - ⚡ AC Power over time  
   - 🔋 DC Power over time  
   - 🔀 AC vs DC Power comparison  
4. Trained a **Linear Regression model**  
5. Predicted DC Power values  
6. Compared predictions with actual values using a scatter plot  
7. Calculated model performance metrics:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
   - Accuracy percentage  

---

## 📊 Results
- The **Linear Regression** model achieved approximately **93% accuracy**.  
- Graphs show how power generation varied through the day and how closely predicted values matched actual DC Power output.

---

## 🛠️ Tools & Libraries
- **Python 3.12**
- **Google Colab**
- **pandas**, **numpy**
- **scikit-learn**
- **matplotlib**, **seaborn**

---

## 📁 Files Included
| File | Description |
|------|--------------|
| `Plant_1_Solar_Prediction_Model_Week2.ipynb` | Main Colab notebook with graphs, model training, and accuracy |
| `README.md` | Documentation for Week 2 tasks |

---

## 🚀 Next Steps (Week 3 Preview)
- Fit multiple ML models (Random Forest, Decision Tree, Gradient Boosting)  
- Compare their accuracies  
- Select the best-performing model for solar energy prediction
