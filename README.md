# Google Play Store App Analysis & Clustering

## Project Overview
This project performs an end-to-end data analysis and market segmentation of the Google Play Store ecosystem. By utilizing Unsupervised Machine Learning techniques—specifically **K-Means** and **DBSCAN**—the study identifies distinct application archetypes based on technical metrics, user sentiment, and market reach.

The analysis provides strategic insights for developers and stakeholders to optimize product positioning and user satisfaction.

## Team Members (National Economics University - NEU)
* **Nguyễn Vân Anh**
* **Đinh Ngọc Minh Châu**
* **Nguyễn Thị Thùy Dương**
* **Đào Hương Giang** (Project Lead)

## Repository Structure
* `DA_GooglePlayStore_Clustering_NEU-5.ipynb`: Main Jupyter Notebook containing data cleaning, EDA, and clustering models.
* `googleplaystore.csv`: Primary dataset containing app details (Rating, Installs, Price, etc.).
* `googleplaystore_user_reviews.csv`: Supplemental dataset for sentiment analysis.
* `requirements.txt`: List of required Python libraries.
* `figures/`: Visualizations exported for the final report.

## Tech Stack
* **Language:** Python 3.x
* **Core Libraries:** * Data Manipulation: `Pandas`, `NumPy`
    * Visualization: `Matplotlib`, `Seaborn`, `Plotly`
    * Machine Learning: `Scikit-learn` (K-Means, DBSCAN, PCA, StandardScaler)

## Key Implementation Steps
1. **Data Engineering:** Schema validation, handling missing values, and identifying shifted rows.
2. **Feature Engineering:** Log-transformation of skewed distributions (Installs, Reviews) and sentiment polarity aggregation.
3. **Clustering Logic:** * Optimization of $K$ using the Elbow Method and Silhouette Analysis.
    * Dimensionality reduction using **Principal Component Analysis (PCA)** for visualization.
4. **Strategic Profiling:** Segmenting the market into five categories: *Market Leaders*, *Rising Stars*, *Premium Niche*, and *Underperformers*.

## Installation
1. Clone the repository:
```bash
git clone [https://github.com/GiangDao-252/Final-DA.git](https://github.com/GiangDao-252/Final-DA.git)
cd Final-DA
```   
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook DA_GooglePlayStore_Clustering_NEU-5.ipynb
```
