# E-commerce Advertisement Click Analysis

## 📌 Project Overview

**E-commerce Advertisement Click Analysis** is a data analysis project focused on understanding customer behavior and identifying factors associated with whether a customer clicks on an advertisement.

The project explores user engagement, demographics, area income, internet usage, and advertisement-related behavior to identify patterns that can support more effective advertising and customer targeting strategies.

## 🎯 Objectives

* Analyze customer characteristics and online behavior.
* Explore factors associated with advertisement clicks.
* Understand relationships between user engagement and ad-click behavior.
* Identify patterns that can support targeted advertising strategies.
* Visualize and interpret relationships within the dataset.

## 📊 Dataset

The project uses an `advertising.csv` dataset containing information about users and their interaction with an e-commerce website.

### Key Features

* **Daily Time Spent on Site** – Time spent by a user on the website each day.
* **Age** – Age of the user.
* **Area Income** – Average income of the geographical area where the user resides.
* **Daily Internet Usage** – Total time spent by the user on the internet each day.
* **Ad Topic Line** – Headline or topic of the advertisement shown to the user.
* **City** – User's location.
* **Clicked on Ad** – Indicates whether the user clicked on the advertisement.

## 🛠️ Technologies Used

* **Python**
* **NumPy** – Numerical computation
* **Pandas** – Data manipulation and analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook**

## 🔄 Analysis Workflow

### 1. Data Loading & Exploration

The dataset was imported using Pandas and examined through:

* Dataset dimensions
* Column names
* Data types
* Missing-value checks
* Statistical summaries
* Initial dataset inspection

### 2. Exploratory Data Analysis

Multiple visualization techniques were used to understand the data and customer behavior:

* Histograms for feature distributions
* Pair plots to examine relationships between variables
* Correlation analysis
* Correlation heatmap
* Advertisement click count plot
* Distribution plot of daily time spent on the website
* Box plots comparing numerical variables based on ad-click behavior

### 3. Feature Analysis

The project examined the relationship between advertisement clicks and:

* Daily time spent on the website
* Age
* Area income
* Daily internet usage

The `City` column was removed during the analysis.

## 📈 Key Insights

The analysis identified relationships between user engagement variables and advertisement-click behavior.

In particular, **Daily Time Spent on Site** and **Daily Internet Usage** showed a strong relationship with each other. The analysis also examined their relationship with the `Clicked on Ad` variable to identify potential behavioral patterns associated with advertisement engagement.

Box plots were used to compare user characteristics between customers who clicked and did not click on advertisements.

## 💡 Business Relevance

The analysis demonstrates how customer behavioral and demographic data can be used to understand advertisement engagement.

These insights can help businesses:

* Understand customer engagement patterns.
* Improve audience segmentation.
* Develop more targeted advertising strategies.
* Identify behavioral characteristics associated with ad engagement.
* Make more informed marketing decisions.

## 📁 Project Structure

```text
E-commerce/
│
├── Project_1 (Prediction of Click-on advertisment by customers on E-commerce company).ipynb
├── advertising.csv
└── README.md
```

## 🚀 How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Place `advertising.csv` in the same directory as the notebook.
4. Open the notebook using Jupyter Notebook or JupyterLab.
5. Run the cells sequentially to reproduce the analysis and visualizations.

## 👤 Author

**Prathamesh Waghmare**

B.Sc. Data Science | MBA – Business Analytics

---

*Academic project focused on exploratory data analysis and understanding customer advertisement engagement in an e-commerce environment.*
