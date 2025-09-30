# Smartphone Customer Reviews Sentiment Analysis 📱

An end-to-end data analytics project that transforms unstructured customer reviews into actionable business insights. This project demonstrates a complete workflow from data collection and cleaning to machine learning and interactive dashboarding.

---

## Project Overview

This project analyzes customer reviews for five leading smartphones to understand public sentiment and identify key product features driving customer satisfaction and dissatisfaction. By leveraging Python for data processing and machine learning, and Power BI for visualization, the project provides a data-driven framework for making strategic recommendations on product selection and feature prioritization.

---

## Key Objectives & Accomplishments

This project successfully demonstrates the following capabilities, as highlighted in my resume:

1.  **Data Collection and Cleaning:**
    * Collected and cleaned unstructured product review data for five distinct smartphone models.
    * Utilized **Python** libraries such as **Pandas** and **NumPy** for data manipulation and **NLTK** for advanced text preprocessing tasks (tokenization, stop-word removal, lemmatization) to prepare the data for analysis.

2.  **Text Analytics and Machine Learning:**
    * Performed machine learning by building and implementing:
        * A **Classification Model** to categorize customer feedback into positive, negative, or neutral sentiment.
        * A **Clustering Model (K-Means)** to identify and group top-performing (and underperforming) features like 'camera', 'battery life', and 'screen quality' across different brands.

3.  **Visualization and Data-Driven Recommendations:**
    * Designed and created interactive **Power BI dashboards** to effectively visualize the analyzed data.
    * The dashboards provide insights that support strategic decision-making, such as identifying a brand's competitive strengths or recommending specific features for future product development.

---

## Tech Stack

* **Data Analysis & Processing:** Python, Pandas, NumPy, NLTK
* **Machine Learning:** Scikit-learn
* **Data Visualization:** Power BI, Matplotlib, Seaborn
* **Version Control & Collaboration:** Git, GitHub, Google Colab

---

## Project Workflow

The project follows a structured, multi-stage workflow:

1.  **Data Acquisition:** Raw review data is scraped from online sources.
2.  **Data Preprocessing:** The text is thoroughly cleaned and standardized in the `01_data_cleaning.ipynb` notebook.
3.  **Modeling & Analysis:** The `02_sentiment_analysis.ipynb` notebook applies classification and clustering algorithms to the cleaned data to derive sentiment scores and feature topics.
4.  **Reporting:** The final processed data is exported and connected to Power BI to build the interactive dashboard for final analysis and insights.
