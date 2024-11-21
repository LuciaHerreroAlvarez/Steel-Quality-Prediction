# Steel Quality Prediction
**Description:**  
A comprehensive analysis to understand the various factors influencing the steel manufacturing process in an Electric Arc Furnace (EAF). This project aims to predict the final carbon and sulfur content in steel, identify key materials used in the process, and optimize energy consumption. Using advanced machine learning techniques and data visualization, this project provides valuable insights into steel quality control.

---

## 🎯 Objectives
- **Analyze the steel manufacturing process**: Investigate the factors that influence the quality of steel in the EAF process, from material charging to refining.
- **Predict the final carbon and sulfur content**: Build predictive models to estimate the final carbon and sulfur content in steel.
- **Optimize energy consumption**: Visualize and analyze energy usage based on transformer power and duration.
- **Identify key materials**: Determine the most commonly used materials in the steel process, such as recycled steel (3A).
- **Analyze composition changes**: Track how the composition of steel changes during the process.

---

## 📊 Summary

### Conclusions:
- **Predictive model for carbon content**: A **Random Forest model** achieved an **R² of 0.74** for predicting the carbon content in steel.
- **Sulfur content prediction challenges**: The sulfur prediction model achieved an **R² of 0.35**, and the key predictor for sulfur was the initial sulfur content, showing that process changes did not significantly affect sulfur levels.
- **Energy consumption insights**: Visualizations revealed the high energy consumption during the steel production process, highlighting potential areas for optimization.
- **Key materials used**: The most commonly used material in the process was **3A**, a recycled steel.

### Challenges faced:
- **Large dataset with multiple tables**: The dataset consisted of 11 tables, making it difficult to merge due to many-to-many relationships in key columns.
- **Temporal indexing and batching**: Data rows were indexed by time, with multiple measurements or additions taken at different times within a batch, adding complexity to the data cleaning process.
- **Sulfur prediction limitations**: Despite efforts, sulfur prediction remained difficult, as its content was predominantly determined by initial conditions, not by the process itself.

### Techniques applied:
- **Data Cleaning & EDA**: Cleaned and pre-processed the dataset, conducted **Exploratory Data Analysis (EDA)** to gain insights into energy usage, material composition, and process behavior.
- **Predictive Modeling**: Built models using **Multiple Linear Regression**, **Gradient Boosting**, and **Random Forest** to predict carbon and sulfur content.
- **Data Visualization**: Created a **Tableau dashboard** to visualize energy consumption, material usage, and composition changes over time.

### Programs used:
- **Python** (Pandas, Scikit-Learn)
- **Tableau** for dashboard visualization.
- **Jupyter Notebooks** for data exploration and analysis.

### Future Work:
- **Energy efficiency analysis**: Given the high energy consumption, a potential next step would be to predict the final steel composition to optimize energy usage.
- **Improving sulfur prediction**: Incorporate additional variables to improve sulfur prediction and better understand how process parameters influence sulfur content.
- **Advanced process modeling**: Develop more sophisticated models that can predict steel quality more accurately, providing better insights into production control and safety.

---

## 📈 Dashboard Image

Here, you can include a screenshot of the Tableau dashboard that shows energy consumption, material usage, and the process changes over time.

![Dashboard](path/to/your_dashboard_image.png)

---

## 🗂️ Data Source

The data used in this project was sourced from **Kaggle** and consists of 11 tables representing different stages of the steel manufacturing process in an Electric Arc Furnace (EAF). The dataset includes key process parameters such as material additions, energy consumption, temperature, and chemical composition across multiple time intervals.

---

## 💻 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/steel-quality-prediction.git
