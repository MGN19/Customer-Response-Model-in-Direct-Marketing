# 📊 Customer Response Model for Direct Marketing Campaigns

### Project Overview:
This project aimed to build a **response model** for a marketing department in a retail food company. The goal was to predict which customers were more likely to respond positively to a new product offer, based on data from a previous marketing campaign. By identifying these customers, the company can optimize its direct marketing campaigns, leading to improved profitability.

This project was completed as part of a group assignment for the Programming for Data Science course.

The project involved various steps of data exploration, feature extraction, and analysis, culminating in a model that can efficiently predict future responses to marketing offers.

<br>

---

### 🎯 Project Objective:
The main objective of this project is to develop a model that can predict which customers are likely to respond positively to a direct marketing campaign. By analyzing data from a previous campaign, the goal was to:

- Discover patterns, trends, and correlations within the customer data. 📈
- Create a set of discriminating characteristics that define the customers who are more likely to purchase the new product. 🛍️
- Build a model that can generalize these findings to the entire customer base, ensuring that future campaigns are more profitable. 💡

<br>

---

### 📊 Data Description:
The dataset consists of **2,240 customers** who were contacted as part of a pilot marketing campaign. It includes **28 socio-demographic**, firmographic, and behavioral features, as well as a flag indicating whether the customer responded to the campaign by purchasing the product. The features are categorized into six main groups:

1. **Socio-Demographic**: Includes variables like BirthYear, Education, MaritalStatus, etc. 👤
2. **Frequency**: Data about the customer's purchase and interaction frequency, e.g., NDealsPurchases, NWebVisitsMonth, etc. 🔄
3. **Monetary Value**: Information on spending patterns, e.g., MntWines, MntMeatProducts, etc. 💰
4. **Customer Lifetime and Satisfaction**: Customer-specific data like CustomerFrom, Complain. 🕒
5. **Campaign Response**: Five response flags corresponding to different campaigns. 📞
6. **Ultimate Campaign Cost and Revenue**: Data related to the cost and revenue generated from the pilot campaign. 📉📈

<br>

---

### 📝 Guidelines:
The project consists of a series of steps that will be completed through **Jupyter Notebooks** and a spreadsheet. The files and their purposes are as follows:

1. **combine.ipynb**: Combines the separate data files from the six extraction calls. 🔗
2. **preprocess.ipynb**: Describes the structure of the dataset, handles missing values, duplicates, and feature transformation. 🧹
3. **extract.ipynb**: Extracts useful features and evaluates feature correlation and redundancy. 🔍
4. **explore1.ipynb**: Assesses individual features' ability to discriminate between respondents and non-respondents, using Scaled mean deviation, Spearman vs Pearson correlation and the chi^2 test of independence. 🔑
5. **explore2.ipynb**: Explores the joint discrimination power of features, aiming to extract precise and representative characteristics of respondents. 🧠
6. **conclusion.ipynb**: Summarizes the findings and provides a detailed yet concise description of the key discriminating features. 📝
7. **respondents.xlsx**: Contains the subset of customers who are more likely to respond to future campaigns based on the selected discriminating features. 📊

<br>

---

The estimated profit was 421MU.

<br>

---

### 🚀 Installation and Setup:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MGN19/Customer-Response-Model-in-Direct-Marketing.git
   ```

▶️ How to Run: All project tasks were conducted in JupyterLab. Run each notebook in the given order:

1. combine.ipynb
2. preprocess.ipynb
3. extract.ipynb
4. explore1.ipynb
5. explore2.ipynb
6. conclusion.ipynb

Excel Output: After completing the notebooks, the final list of respondents were saved as respondents.xlsx, which can be used for the next campaign. 📊
