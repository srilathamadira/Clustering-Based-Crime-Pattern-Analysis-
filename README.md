# Clustering-Based Crime Pattern Analysis

## 📌 Project Overview
Crime analysis is a critical task for improving public safety and supporting law enforcement decision-making. With the rapid growth of urban populations, large volumes of crime data are generated daily. Manual analysis of such data is inefficient and fails to uncover hidden patterns.

This project applies **clustering-based machine learning techniques** to analyze large-scale crime datasets and identify **crime hotspots and patterns** based on spatial and temporal attributes.

---

## 🎯 Objectives
- To analyze large-scale crime datasets using unsupervised learning
- To identify crime hotspots based on location data
- To discover hidden crime patterns without labeled data
- To visualize crime clusters for better interpretation
- To support data-driven crime prevention strategies

---

## 📂 Dataset Description
- **Dataset Type:** Public Crime Dataset  
- **Source:** Kaggle / Official Crime Data Portals  
- **Dataset Size:** **1,048,576 crime records (~1 million entries)**  
- **Attributes Used:**
  - Crime Type
  - Date & Time
  - Latitude
  - Longitude
 
    
https://www.kaggle.com/code/jockeroika/crime-analysis
---

## 🧠 Methodology
1. Data Collection from public crime datasets  
2. Data Preprocessing and Cleaning  
3. Feature Selection (Spatial & Temporal features)  
4. Clustering using:
   - K-Means
   - DBSCAN  
5. Hybrid Clustering (K-Means + DBSCAN)  
6. Visualization of crime hotspots  
7. Pattern analysis and interpretation  

---

## 🔀 Hybrid Model
A **hybrid clustering model** is used to improve clustering quality:
- **K-Means** performs initial grouping of crime data
- **DBSCAN** refines clusters by identifying dense regions and removing noise

This approach combines the strengths of both algorithms for better hotspot detection.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python
- **Development Environment:** Google Colab / VS Code
- **Libraries:**
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn

---

## 💻 System Requirements

### Software
- Python 3.x
- Any IDE (VS Code recommended)

### Hardware
- Minimum 8 GB RAM
- Stable Internet Connection

---

## 📊 Results
- Identification of crime hotspots
- Clustered visualization of crime-prone regions
- Improved understanding of spatial and temporal crime patterns

---

## 🚀 Future Enhancements
- Integration of real-time crime data
- Crime prediction using time-series models
- Web-based interactive dashboard
- Advanced deep learning models

---

## 👩‍🎓👨‍🎓 Team Members
- Srilatha Madira  
- Kamepally Nikhil Sai  

---

## 📜 Conclusion
This project demonstrates the effectiveness of clustering-based machine learning techniques in analyzing large-scale crime data. The system successfully identifies crime hotspots and hidden patterns, contributing to smarter and safer urban planning.

---

## 📎 License
This project is for academic and educational purposes only.
