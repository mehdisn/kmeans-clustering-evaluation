# K-means Clustering Evaluation

This project applies **K-means clustering** on health-related data and evaluates the clustering performance using a **purity score**. The dataset includes various patient records, potentially involving blood donors and hepatitis cases. The goal is to explore how well the K-means algorithm clusters the data and aligns it with known labels.

## Features
- **K-means Clustering**: Implementation of the K-means algorithm with custom initialization and iteration logic.
- **Purity Score**: Evaluates clustering performance by comparing clusters to known labels.
- **Data Preprocessing**: Handles missing values and converts categorical features to numeric form.
- **Health Dataset**: Clusters patient data to reveal potential patterns.

## Dataset
The project uses a dataset named **`hcvdat0.csv`**, where:
- **Gender**: Encoded as `0` for male and `1` for female.
- **Labels**: Different health conditions such as:
  - `0`: Blood Donor
  - `1`: Suspected Blood Donor
  - `2`: Hepatitis
  - `3`: Fibrosis
  - `4`: Cirrhosis

Missing values are filled with the **mean** of respective columns for cleaner analysis.
