#  Predictive Data Analytics – Customer Behaviour Case Study  
### CAB330 (Data & Web Analytics) – Queensland University of Technology

---

##  1. Overview

This repository contains a full analytical case study completed for  
**CAB330 – Data and Web Analytics at QUT**.

The project explores **customer behaviour patterns** using four datasets:

- **Audio Track Features**  
- **Retail Transactions**  
- **Movie Descriptions**  
- **Weblog (server log) data**

Across these datasets, the objective is to extract insights into customer segments, purchase patterns, text-based recommendations, and website navigation behaviour.

---

##  2. Business Questions

This study answers four key analytics questions:

1. **Customer Segmentation**  
   - What user groups can be identified based on behavioural or purchasing patterns?

2. **Market Basket Analysis**  
   - Which product combinations are frequently purchased together?

3. **Content Recommendation**  
   - How can we recommend similar movies based on textual descriptions?

4. **Web Usage Mining**  
   - What are the most common browsing paths taken by users on the website?

---

##  3. Techniques & Tools

### **Programming & Data Processing**
- Python, pandas, numpy

### **Clustering**
- K-means  
- Hierarchical clustering  
- Silhouette score  
- Elbow method  
- Pairplots  

### **Association Rule Mining**
- Apriori  
- Support, Confidence, Lift metrics  

### **Text Mining**
- TF–IDF vectorisation  
- Cosine similarity  
- Content-based recommendation  

### **Web Usage Mining**
- Session identification  
- Path analysis  
- Frequency analysis of navigation patterns  

### **Visualisation**
- matplotlib  
- seaborn  

---

##  4. Repository Structure

## 4. Repository Structure

```text
data/
├── processed/                  # Cleaned datasets (if applicable)
├── raw/                        # Original datasets
│   ├── Dataset1_AudioTrack.csv
│   ├── Dataset2_TRANS.csv
│   ├── Dataset3_Movie.csv
│   └── Dataset4_Weblog.txt
figures/                        # Visualisations generated during the analysis
├── T1_{col}_by_cluster.png
├── T1_elbow.png
├── T1_energy_hist.png
├── T1_pairplot_k3.png
└── T1_silhouette.png
notebooks/
└── cab330_case_study.ipynb     # Main Jupyter notebook for the analysis
reports/
└── cab330_case_study_report.docx # Final written report
README.md
requirements.txt



