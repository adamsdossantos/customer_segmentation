# Customer Segmentation with K-means Clustering
 

## 1. Project Overview

This project implements a K-means clustering algorithm to segment customers based on their purchasing behavior and demographic information. The goal is to identify distinct customer groups that can be targeted with specific marketing strategies, helping businesses better understand their customer base and tailor their services.


## 2. Dataset Source

https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## 2. Features
- **Data Preprocessing**: Data cleaning, normalization, and splitting into training and testing sets.
- **Model Training**: Applying K-means clustering to segment customers into distinct groups.
- **Model Evaluation**: Evaluating the clustering results using metrics like inertia and the silhouette score to determine the optimal number of clusters.
- **Visualization**: Visualization of clusters using 2D and 3D plots for better understanding of customer segments.



## 3. Project Structure
    ├── Mall_Customers.csv           # Dataset file 
    ├── house_pricing.ipynb         # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 4. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- xgboost
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/customer_segmentation.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook customer_segmentation.ipynb
```
## 5. Usage

Open the customer_segmentation.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the Mall_Customer.csv and perform data cleaning, scaling, and normalization.
- **Model Training**: Apply the K-means clustering algorithm and use the elbow method or silhouette score to determine the optimal number of cluster.
- **Model Evaluation**: Evaluate the quality of the clusters and visualize them using scatter plots.
- **Visualization**: Visualize the clusters in 2D or 3D, showcasing the customer segments and analyzing their characteristics.


## 6. Results in Test


| Metric    |  Value   |
|-----------|----------|
| Optimal Number of Clusters  |  5   |
| Inertia |  44448   |
|Silhouette Score | 0.55|


## 7. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 8. License

This project is licensed under the MIT License - see the LICENSE file for details.







