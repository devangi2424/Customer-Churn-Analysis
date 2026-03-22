# Customer Churn Analysis Project

## Project Overview

Customer churn is a major challenge for subscription-based and service-oriented businesses. Identifying customers who are likely to leave allows organizations to take proactive measures to improve retention and reduce revenue loss.

This project focuses on analyzing customer behavior and identifying churn patterns using data preprocessing, feature engineering, and clustering techniques. By applying **K-Means clustering**, the project segments customers into meaningful groups based on their characteristics and behavior.

The results help identify high-risk customer segments and provide insights that businesses can use to develop targeted retention strategies.

---

## Objectives

The main objectives of this project are:

- Analyze customer data and identify patterns related to churn.
- Preprocess and clean the dataset for analysis.
- Apply scaling and feature transformation techniques.
- Determine the optimal number of clusters using clustering evaluation methods.
- Perform customer segmentation using **K-Means clustering**.
- Visualize the clusters and interpret customer behavior within each segment.

---

## Project Structure

```
Customer-Churn-Analysis/
│
├── data/
│   ├── raw/
│   │   └── customer_churn_dataset.csv
│   │
│   └── processed/
│       └── preprocessed_data.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── models/
│   └── kmeans_model.pkl
│
├── docs/
│   ├── project_report.pdf
│   └── results_and_visualizations
│
├── README.md
└── requirements.txt
```

---

## Folder Description

### data/

Contains the dataset used in the project.

- **raw/** – Contains the original dataset.
- **processed/** – Contains the cleaned and preprocessed dataset used for modeling.

### notebooks/

Contains Jupyter notebooks used for the analysis and model development.

Includes steps such as:

- Data exploration
- Data preprocessing
- Feature scaling
- Cluster analysis
- Visualization

### models/

Stores trained machine learning models used in the project.

Example:

- Trained **K-Means clustering model**

### docs/

Contains important documentation and results related to the project.

Includes:

- Project report
- Visualizations
- Results explanation

---

## Technologies Used

The project is implemented using the following technologies and libraries:

- Python
- Jupyter Notebook
- Pandas – Data manipulation
- NumPy – Numerical computations
- Matplotlib
- Seaborn – Data visualization
- Scikit-learn – Machine learning algorithms
- K-Means Clustering – Customer segmentation
- Git
- GitHub – Version control and collaboration

---

## Methodology

The project follows the following workflow.

### Data Collection

The dataset contains customer-related information such as:

- Customer demographics
- Service usage
- Account details

These attributes may influence churn behavior.

### Data Preprocessing

The dataset was cleaned and prepared using the following steps:

- Handling missing values
- Removing irrelevant columns
- Encoding categorical variables
- Converting data types where necessary

### Feature Scaling

Feature scaling was applied to ensure that all variables contribute equally to the clustering algorithm.

Techniques used include:

- Standardization
- Normalization

### Determining Optimal Clusters

The **Elbow Method** was used to determine the optimal number of clusters for K-Means.

This method evaluates the **Within-Cluster Sum of Squares (WCSS)** for different numbers of clusters to find the best segmentation.

### K-Means Clustering

K-Means clustering was applied to segment customers into different groups based on their characteristics.

Example clusters include:

- High-value loyal customers
- Customers with moderate engagement
- Customers with high churn risk

### Visualization

Cluster results were visualized using graphs and plots to interpret the segmentation and understand customer behavior patterns.

---

## Key Insights

The clustering analysis revealed several important insights:

- Some customer segments show **higher likelihood of churn** due to lower engagement.
- Certain clusters represent **loyal and high-value customers**.
- Identifying these segments allows businesses to develop **targeted retention strategies**.

---

## How to Run the Project

Follow the steps below to run the project on your local machine.

### Clone the Repository

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
```

### Navigate to the Project Directory

```bash
cd customer-churn-analysis
```

### Install Required Dependencies

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

```bash
jupyter notebook
```

Then open the notebook located in the **notebooks** folder.

---

## Team Collaboration

This project is developed collaboratively using GitHub.

Team members can contribute by:

- Cloning the repository
- Creating a new branch
- Making changes or adding features
- Committing updates
- Submitting a Pull Request

Example workflow:

```bash
git checkout -b feature-name
git add .
git commit -m "Added new analysis"
git push origin feature-name
```

---

## Results

The project successfully:

- Prepared and cleaned the dataset
- Applied clustering techniques for segmentation
- Identified meaningful customer groups
- Provided insights that can help businesses reduce churn

The clustering model and visualizations demonstrate how machine learning can support customer retention strategies.

---

## Future Improvements

Possible future improvements include:

- Applying classification models such as **Logistic Regression** or **Random Forest** to predict churn.
- Using advanced clustering methods like **DBSCAN** or **Hierarchical Clustering**.
- Integrating dashboard visualization tools such as **Power BI** or **Tableau**.
- Deploying the model as a **web application or API**.

---

## Contributors

- Diksha Sharma
- Devangi Patel
- Krish Patel
- Priyanka Panchal
- Yash Thakkar

---

## License

This project is created for **academic and educational purposes**.
