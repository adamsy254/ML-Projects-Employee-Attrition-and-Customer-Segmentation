# 🚀 Machine Learning Projects: Employee Attrition & Customer Segmentation 🤖📊

**Python ML Portfolio** – Turning raw data into **predictive insights and customer understanding**!  
Mastering end-to-end machine learning pipelines: data cleaning, feature engineering, supervised classification, unsupervised clustering, model evaluation, and actionable business insights using Python and scikit-learn. 🌟

## 📈 Featured Projects

### 👥 Project 1: Employee Attrition Prediction (Supervised Classification) 🏢
**"Predicting who will leave – before they do!"** 🔮  
A complete classification pipeline to help HR reduce turnover and retain top talent.

- **Dataset**: **1,470 employees** with 35 detailed HR features (job role, satisfaction, overtime, distance from home, years at company, promotions, etc.).
  - Imbalanced target: Only **16.1% attrition** (237 Yes vs. 1,233 No) – real-world challenge handled with care ⚖️
- **Data Magic Performed** ✨:
  - Deep cleaning: Removed constant/uninformative columns (EmployeeCount, Over18, StandardHours), dropped unique ID 🧹
  - Smart feature categorization: 7 nominal, 9 ordinal, 12 continuous, 2 discrete for proper preprocessing
  - Creative feature engineering: Built **PromotionDelayRatio**, **CompanyTenureRatio**, **AvgYearsPerCompany** to reveal career stagnation and job-hopping patterns 🚀
  - Stratified train-test split (80/20) to maintain class distribution and prevent data leakage
- **Key Insights Uncovered** 🔥:
  - Attrition strongly tied to slow promotions, short tenure, low job satisfaction, and overtime
  - Engineered ratios highlighted hidden drivers like delayed career growth and instability
  - Pipeline fully prepared for advanced modeling (logistic regression, random forest, XGBoost, etc.)
- **Tools & Tricks**: Pandas, NumPy, scikit-learn (train_test_split, stratification), Jupyter notebooks, detailed reports with formatted summaries 📓

### 🛒 Project 2: Online Supermarket Customer Segmentation (Unsupervised Clustering) 🏪
**"Every customer shops differently – let’s find out how!"** 🎯  
Uncovering hidden customer groups to power personalized marketing and inventory strategies.

- **Dataset**: **30,000 orders** from **10,239 unique customers**, including discount %, shopping time (weekday/hour), and % spend across 8 categories (Food, Fresh, Drinks, Home, Beauty, Health, Baby, Pets).
- **Data Magic Performed** ✨:
  - Aggregated order-level data to customer-level profiles: avg items per order, avg discount, preferred shopping hour/weekday
  - Engineered **category entropy** to quantify shopping diversity (focused vs. varied buyers)
  - Standardized all features for balanced clustering
  - Evaluated multiple k values using **silhouette score (max 0.282 at k=3)**, Davies-Bouldin, and Calinski-Harabasz indices
- **Delicious Insights Served Hot** 🔥:
  - **Cluster 0 (8,163 customers – 80%)**: Everyday multi-category shoppers – balanced spending, moderate discounts – the reliable core base 🛍️
  - **Cluster 1 (408 customers)**: Extreme discount hunters – **91% avg discount**, **96% spent on Food**, near-zero entropy – bulk bargain lovers! 💸
  - **Cluster 2 (1,668 customers)**: Niche baby & beauty shoppers – **60% Baby + 25% Beauty**, low order volume – ideal for targeted campaigns 👶💄
- **Tools & Tricks**: Pandas for aggregation, scikit-learn (K-Means, StandardScaler, clustering metrics), Matplotlib/Seaborn visualizations, PCA exploration, detailed cluster profiling 📊

## Technologies Used
- Python 3.x
- Libraries: pandas, numpy, scikit-learn (for preprocessing, clustering, metrics), matplotlib/seaborn (for visualizations)
- Notebooks: Jupyter (part_A.ipynb, Part_2.ipynb)
- Reports: Word docs (PART A.docx, PART B.docx) with objectives, approaches, insights, and references.

## Files in This Repo
- **part_A.ipynb**: Jupyter notebook for Part A (data prep, feature engineering, summaries).
- **PART A.docx**: Report for Part A with objectives, approach, insights, and references.
- **Part_2.ipynb**: Jupyter notebook for Part B (clustering pipeline, visualizations).
- **PART B.docx**: Report for Part B with clustering details, profiles, and references.
- **ML Methods using Python.docx**: Instructions and problem statements for both parts.
- Datasets: (Add if uploading, e.g., Part_A_Dataset.xlsx, Part_B_Dataset.csv – note: GitHub has file size limits; use Git LFS for large files).
- Images: Screenshots/figures from reports (e.g., image1.png for charts).

## How to Run
1. Clone the repo: `git clone https://github.com/adamsy254/ML-Projects-Employee-Attrition-and-Customer-Segmentation.git`
2. Install dependencies: `pip install -r requirements.txt` (Create a requirements.txt with: pandas, numpy, scikit-learn, matplotlib, seaborn)
3. Run notebooks: Open in Jupyter (`jupyter notebook`) and execute cells.
4. Assumptions: No missing data in datasets; stratified splits for imbalance; K-Means for simplicity.

## Key Insights
- Part A: Attrition linked to tenure, promotions, satisfaction; class imbalance handled via stratification.
- Part B: 3 clusters identified (e.g., regular shoppers, discount bulk buyers, niche baby/beauty focused).

These projects showcase **real-world ML workflows** – from messy data to clean features, robust modeling choices, and interpretable results that drive decisions! 🚀

## ❤️ Support My Work & Let's Collaborate!
If these projects inspired you 😄, helped with your studies/portfolio, or you need **custom machine learning solutions, predictive models, or data analysis** – I’m here to help!  
- **Buy Me a Coffee (or Data!) ☕**: Donate via PayPal → [adamsmuema19@gmail.com](https://www.paypal.com/donate/?hosted_button_id=UW2NDM92AU67U)
- **Need Insights, Dashboards, or Training? 📩**: Hit me up on WhatsApp → [+254702896107](https://wa.me/254702896107)

Your support fuels more open-source ML projects and knowledge sharing! 🌍✨ Thank you! 🫶
