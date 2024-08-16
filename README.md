# RFM Analysis and Clustering Using Business Intelligence Methodologies

# The use of Business Intelligence (BI) methodologies on customer relationship management (CRM): Applied solutions for an E-commerce website.

This repository contains the implementation of RFM (Recency, Frequency, Monetary) analysis and customer clustering, leveraging Business Intelligence (BI) methodologies to enhance Customer Relationship Management (CRM) strategies.

## Project Overview

Customer Relationship Management (CRM) is a crucial component for businesses to understand and manage customer interactions. In this project, we utilize RFM analysis, a powerful technique to segment customers based on their purchase behavior, and clustering algorithms to further refine these segments. The goal is to provide actionable insights that can be used to tailor marketing strategies and improve customer retention.

## Contents

- **`DW RFM&Clustering.ipynb`**: The main Jupyter Notebook where the RFM analysis and clustering are implemented. The notebook includes data preprocessing, RFM metric calculation, customer segmentation using clustering algorithms, and data visualization.

## Key Features

- **RFM Analysis**: 
  - **Recency**: Measures how recently a customer made a purchase.
  - **Frequency**: Measures how often a customer makes a purchase.
  - **Monetary**: Measures how much money a customer spends on purchases.

- **Customer Segmentation**:
  - Customers are segmented based on RFM scores.
  - Clustering techniques (e.g., K-Means) are applied to group customers into distinct segments.

- **Data Visualization**:
  - Visualizations include scatter plots, bar charts, and other graphical representations to help understand the distribution and characteristics of the customer segments.

## Getting Started

### Prerequisites

To run the notebook, you'll need the following installed on your system:

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Prberte/RFM-analysis---The-use-of-Business-Intelligence-BI-methodologies-on-customer-relationship-management.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd RFM-analysis---The-use-of-Business-Intelligence-BI-methodologies-on-customer-relationship-management
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook "DW RFM&Clustering.ipynb"
   ```

### Usage

1. Open the Jupyter Notebook.
2. Follow the instructions provided in each cell of the notebook.
3. Modify the code or input data as needed to apply RFM analysis and clustering to your own dataset.

### Data

The notebook is designed to work with transactional data that includes at least the following columns:

- `CustomerID`: Unique identifier for each customer.
- `InvoiceDate`: Date of the transaction.
- `InvoiceNo`: Unique identifier for each transaction.
- `Quantity`: Number of items purchased in the transaction.
- `UnitPrice`: Price per item.

### Output

- **RFM Scores**: Customers are scored based on Recency, Frequency, and Monetary values.
- **Clusters**: Customers are grouped into clusters, which can be visualized and analyzed for further insights.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## Acknowledgments

- This project was inspired by the need to enhance customer understanding and segmentation using data-driven approaches.
- Special thanks to the open-source community for providing tools and libraries that make projects like this possible.
