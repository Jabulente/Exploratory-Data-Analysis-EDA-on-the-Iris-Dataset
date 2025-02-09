# **Exploratory Data Analysis (EDA) on the Iris Dataset**  

![species-of-IRIS-flower](Resources/Three-species-of-IRIS-flower(0).jpg)

## **Project Overview**  

This project focuses on performing *Exploratory Data Analysis (EDA)* on the **Iris Dataset**, a well-known dataset in machine learning and statistics. The goal is to understand the dataset’s structure, identify patterns, detect outliers, and explore feature relationships. The insights from this analysis can be used for further research, classification modeling, and improving data-driven decision-making.  

## **Dataset Information**  

The **Iris Dataset** contains **150 observations** of iris flowers from three different species:  

| Species      | Number of Samples |
|-------------|------------------|
| *Setosa*    | 50               |
| *Versicolor*| 50               |
| *Virginica* | 50               |

Each sample includes **four features** representing flower measurements:

| Feature         | Description                           | Unit (cm) |
|---------------|-----------------------------------|----------|
| Sepal Length | Length of the sepal | cm |
| Sepal Width  | Width of the sepal  | cm |
| Petal Length | Length of the petal | cm |
| Petal Width  | Width of the petal  | cm |
| Species      | Flower species classification | N/A |

The dataset is widely used for classification tasks, helping researchers and data analysts understand fundamental machine learning concepts.

---

## **Analysis Coverage**  

This EDA project includes the following major sections:  

### **1. Data Preprocessing**
- Checking for **missing values** (if any).
- Ensuring **correct data types**.
- Validating **data consistency**.

### **2. Statistical Summary**
- Computing **mean, median, standard deviation, minimum, and maximum** for each feature.
- Analyzing **feature distributions** to understand variability.

### **3. Data Visualization**
- **Pair plots** to observe relationships between different features.
- **Histograms & box plots** to analyze distributions and detect outliers.
- **Correlation heatmap** to explore feature relationships.

### **4. Outlier Detection**
- Identifying and visualizing **outliers** using **box plots**.
- Using **scatter plots** to observe deviations.

### **5. Species-Wise Feature Analysis**
- Comparing the **mean and variance** of flower measurements per species.
- **Scatter plots** to observe feature separation among species.

### **6. Feature Relationships**
- Exploring **correlations** between numerical features.
- Analyzing **which features contribute most** to species differentiation.

---

## **Goals of the Analysis**  
Through this EDA, we aim to:  
✅ Understand the **basic structure** of the Iris dataset.  
✅ Identify **key features** that differentiate species.  
✅ Provide **visualizations** to summarize data insights.  
✅ Lay the foundation for **machine learning classification models**.

---

## **Results Summary (Mean Comparisons)**  

| Species     | sepal length (cm)   | sepal width (cm)   | petal length (cm)   | petal width (cm)   |
|:-----------|:--------------------|:-------------------|:--------------------|:-------------------|
| setosa     | 5.01 ± 0.05 c       | 3.43 ± 0.05 c      | 1.46 ± 0.02 c       | 0.25 ± 0.01 c      |
| versicolor | 5.94 ± 0.07 a       | 2.77 ± 0.04 a      | 4.26 ± 0.07 a       | 1.33 ± 0.03 a      |
| virginica  | 6.59 ± 0.09 b       | 2.97 ± 0.05 b      | 5.55 ± 0.08 b       | 2.03 ± 0.04 b      |
| p-value    | 0.0000***           | 0.0000***          | 0.0000***           | 0.0000***          |

Key insights:  
🔹 *Setosa* has the **smallest petal and sepal sizes**, making it the easiest to classify.  
🔹 *Versicolor* and *Virginica* have **overlapping sepal lengths**, making classification harder.  
🔹 Petal length and petal width are **strong indicators** of species classification.

---

## **Conclusion**  
This **EDA of the Iris dataset** provides valuable insights into the structure and relationships between features. The analysis highlights that **petal length and width are the most distinguishing features** among species, making them essential for building a **classification model**.  

This project can be further extended by applying **classification algorithms** such as Decision Trees, k-Nearest Neighbors (KNN), or Support Vector Machines (SVM) to predict species based on flower measurements.  

---

## **Technology & Tools Used**  
🟢 Python (Pandas, NumPy, Matplotlib, Seaborn, Statmodel, Sklearn)  
🟢 Jupyter Notebook 

---

## **How to Use This Project**  
1. Clone the repository:  
   ```bash
   git clone [https://github.com/your-username/iris-eda.git](https://github.com/Jabulente/Exploratory-Data-Analysis-EDA-on-the-Iris-Dataset.git)
   ```

3. Run the Jupyter Notebook to explore the analysis.

---

### **Author**  
**Jabulente** – Data Analyst | Data Scientist
