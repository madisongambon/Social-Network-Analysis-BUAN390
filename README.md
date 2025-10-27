# Reddit Network and Sentiment Analysis (BUAN 390 Capstone)

**Author:** Madison Taylor Gambon  
**Course:** Business Analytics Strategy (BUAN 390)  
**University of San Diego**  
**Date:** May 2025  

This project combines social network analysis and natural language processing to explore emotional expression, influence, and engagement dynamics within the **r/RealHousewives** subreddit. It uses data scraped from Reddit (via the PRAW API) and applies Python-based modeling to identify influential users, sentiment trends, and emotionally impactful contributors.

---

## Objectives
- Identify the most influential users based on network centrality metrics.
- Analyze sentiment and emotion within user comments.
- Model how sentiment and engagement relate using **probit regression**.
- Introduce a custom **“Drama Index”** combining emotional intensity and influence.

---

## Methods
- **Data Collection:** Reddit API (PRAW)
- **Network Construction:** NetworkX directed graph
- **Sentiment Analysis:** TextBlob (polarity, subjectivity)
- **Emotion Detection:** text2emotion package
- **Modeling:** `statsmodels.discrete.discrete_model.Probit`  
- **Visualization:** matplotlib, seaborn, and Gephi exports

---

## Key Findings
- **Influence** is concentrated among a small number of highly connected users.
- **Sentiment** skews neutral to moderately positive, with emotion words such as *happy*, *sad*, and *fear* most common.
- **Probit regression** showed that PageRank centrality significantly predicted influencer status.
- The **Drama Index** revealed users who were both structurally central and emotionally expressive, making them key drivers of engagement.

---

## Skills Demonstrated
Python • Pandas • NetworkX • TextBlob • Text2Emotion • Statsmodels (Probit) • Data Visualization • Report Writing • Business Interpretation

---

## Repository Contents
| Folder | Description |
|--------|--------------|
| `notebooks/` | Jupyter notebook containing data analysis and modeling code |
| `reports/` | Final white paper and presentation slides |


---


