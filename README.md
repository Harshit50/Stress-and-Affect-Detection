# 🏥 MIMIC-III Clinical Data Analytics

This project explores patient-level healthcare data from the **MIMIC-III database**, aiming to identify hidden patterns in clinical records through **data integration, cleaning**, and **unsupervised machine learning techniques**.

The goal is to gain meaningful insights from complex clinical datasets by applying clustering algorithms to patient demographics, lab results, and physiological data.

---

## 📌 Objective

To preprocess and unify diverse clinical datasets and apply clustering (K-means & Hierarchical) to identify patient subgroups and extract actionable healthcare insights.

---

## 🗂 Dataset

- **Source**: [MIMIC-III Database](https://physionet.org/content/mimiciii/1.4/)
- Contains de-identified health data of ~60,000 ICU patients
- Used subsets: 
  - **LABEVENTS.csv** (Lab test results)  
  - **CHARTEVENTS.csv** (Physiological measurements)  
  - **PATIENTS.csv** (Demographics)  

⚠️ *Access requires credentialed approval via PhysioNet.*

---

## 🛠️ Technologies Used

- **Python**  
- **Pandas** – data manipulation & merging  
- **NumPy** – numerical operations  
- **Scikit-learn** – clustering algorithms  
- **Matplotlib & Seaborn** – visualization  

---

## 🧪 Key Steps

1. **Data Integration**  
   - Merged `LABEVENTS`, `CHARTEVENTS`, and `PATIENTS` tables on patient identifiers  
   - Created a unified dataset for downstream analysis

2. **Data Cleaning & Preprocessing**  
   - Removed null values, duplicates, and inconsistent entries  
   - Normalized and encoded categorical variables  
   - Ensured 95% data reliability post-cleaning

3. **Clustering Techniques Applied**  
   - **K-means Clustering**: Patient grouping based on lab and physio data  
   - **Hierarchical Clustering**: Dendrogram analysis to visualize similarity  
   - Evaluated cluster cohesion and visualized with cluster plots

4. **Visualization**  
   - Histograms of patient vitals  
   - Cluster plots to show subgroup distinctions  
   - Heatmaps of lab results

---

## 📈 Results & Insights

- Successfully segmented patients into meaningful clusters
- Discovered patterns across age, lab metrics, and ICU stays
- Helped demonstrate the potential of clustering for patient risk stratification





