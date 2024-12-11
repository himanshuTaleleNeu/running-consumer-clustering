# 🏃‍♂️ Data Mining Project: Running Consumer Clustering Analysis

This project is an end-to-end clustering analysis aimed at assisting a running footwear and apparel company in making strategic decisions regarding its product offerings and marketing strategies. Using survey data from consumers, this project identifies key consumer segments through unsupervised learning techniques and provides actionable recommendations.

---

## 🎯 Objective

The objective of this project is to perform clustering analysis on survey data collected from running consumers to:
- Identify key consumer segments.
- Provide actionable insights for product portfolio customization.
- Recommend personalized marketing strategies to the company.

---

## 🛠️ Project Workflow

The project consists of the following major steps:

1. **Data Preparation**:
   - Cleaned and preprocessed survey data to handle missing values and normalize features.
   - Used appropriate scaling techniques for clustering.

2. **Similarity Metric & Matrix**:
   - Calculated similarity metrics (Euclidean and cosine) to assess relationships between data points.

3. **Clustering Algorithm**:
   - Applied K-means clustering to group consumers into meaningful segments.
   - Determined the optimal number of clusters using the Elbow Method and silhouette scores.

4. **Dimensionality Reduction**:
   - Performed Principal Component Analysis (PCA) to visualize the clusters in a 2D space.

5. **Interpretation of Results**:
   - Analyzed cluster characteristics to identify patterns in running habits and preferences.
   - Provided recommendations for product customization and personalized marketing.

---

## 📊 Dataset

The dataset comprises survey responses from a pool of participants who answered questions regarding their running habits and preferences. Key attributes include:
- Demographics
- Running frequency
- Preferred products
- Brand loyalty
- Spending habits

The data preprocessing steps included:
- Handling missing data.
- Normalizing numerical features.
- Encoding categorical variables as necessary.

---

## 🧪 Techniques Used

The following tools and methodologies were employed:

- **Clustering**:
  - K-means algorithm to segment consumers.
  - Elbow Method to find the optimal number of clusters.
  - Silhouette scores for validation.
- **Dimensionality Reduction**:
  - PCA for visualizing high-dimensional data.
- **Similarity Metrics**:
  - Euclidean distance and cosine similarity.
- **Visualization**:
  - Used seaborn and matplotlib for exploratory and clustering analysis.

---

## 🔍 Results and Insights

### Key Findings:
1. **Consumer Segments Identified**:
   - Distinct clusters of running enthusiasts, casual joggers, and competitive runners.
   - Segments also reflected preferences for premium products versus budget-friendly options.

2. **Product Portfolio Customization**:
   - Recommended focusing on specific products like lightweight shoes for competitive runners and durable apparel for regular joggers.

3. **Marketing Strategies**:
   - Suggested personalized marketing campaigns targeting specific consumer needs:
     - Competitive runners: Highlight performance-enhancing products.
     - Casual joggers: Focus on comfort and affordability.

4. **Visualization**:
   - PCA plots provided a clear representation of consumer segments in 2D space, aiding in interpreting clustering results.

---

## 🚀 How to Run the Project

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/himanshuTaleleNeu/running-consumer-clustering.git

---
## 📌 Conclusion

This project demonstrates the power of data mining and clustering techniques in deriving actionable business insights. By leveraging survey data and advanced unsupervised learning methods, we successfully segmented running consumers and proposed strategies to optimize product offerings and marketing efforts. The analysis provides a foundation for tailoring product portfolios and enhancing customer experiences through personalized engagement.

---

## 🚀 Tools Used

- **Python Libraries**: pandas, numpy, matplotlib, seaborn, sklearn
- **Jupyter Notebook**: Used for coding and documenting the project.
- **Excel**: For initial dataset review and data cleaning.

---
