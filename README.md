# **Book Clustering Analysis**

## **Project Overview**
This project explores clustering techniques applied to the Goodreads 10k dataset to uncover meaningful groupings of books based on features like publication year, average rating, and popularity. Using K-Means clustering and advanced visualizations, the analysis provides insights into book characteristics, their engagement levels, and potential marketing strategies. The findings demonstrate the utility of clustering for segmentation and recommendations in the literary domain.

---

## **Key Features**
1. **Data Analysis**:
   - Examined metadata and user interactions from the Goodreads dataset.
   - Performed feature engineering to calculate `Total Ratings`, `Avg Rating`, and `Publication Year`.

2. **Clustering Analysis**:
   - Used K-Means clustering to segment books into four clusters.
   - Validated the clustering process with the Elbow Method.

3. **Visualizations**:
   - Visualized clusters using PCA and boxplots to highlight differences in ratings, popularity, and temporal trends.

4. **Actionable Insights**:
   - Provided strategic recommendations for marketing and recommendation systems based on cluster profiles.

---

## **Technologies Used**
- **Python**:
  - Data Manipulation: `pandas`
  - Visualizations: `matplotlib`, `seaborn`
  - Clustering: `scikit-learn`
- **Jupyter Notebook**: For iterative analysis and visualization.

---

## **Dataset**
- **Source**: [Goodreads 10k Dataset (Cleaned)](https://www.kaggle.com/datasets/sahilkirpekar/goodreads10k-dataset-cleaned)
- **Description**:
  - Metadata and user interaction data for 10,000 books.
  - Features include titles, publication years, average ratings, and user engagement metrics.

---

## **Project Files**
- **Report**: A comprehensive PDF summarizing the analysis, visualizations, and findings.
- **Code**:
  - Jupyter Notebook: Contains all steps for data preparation, clustering, and visualization.
  - Exported Dataset: The clustered data saved as `clustered_books.csv`.

---

## **Key Findings**
1. **Cluster Profiles**:
   - Cluster 0: Older classics (~1988) with high average ratings (~4.06) and significant popularity.
   - Cluster 1: Newer books (~1993) with high engagement but lower ratings (~3.58).
   - Cluster 2: Anomalous entries (~526 AD), likely due to mislabeled publication years.
   - Cluster 3: Midlist books (~1995) with moderate ratings and lower engagement.
   
2. **Strategic Insights**:
   - Promote Cluster 0 titles as high-quality classics.
   - Reassess marketing for Cluster 3 to improve visibility.
   - Address data quality issues in Cluster 2 for cleaner future analyses.

---

## **How to Reproduce**
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Book-Clustering-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Book-Clustering-Analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook for analysis or view the report for insights.

---

## **License**
This work is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).

### **What This Means**
Under this license:
- **You may view, use, and share** this project for non-commercial purposes.
- **You cannot modify or adapt** the code or outputs.
- **Attribution Required**: You must credit the original author (me) when sharing this project.

This license ensures that my work remains unchanged and is used only for educational or non-commercial purposes.

---
Thank you!
