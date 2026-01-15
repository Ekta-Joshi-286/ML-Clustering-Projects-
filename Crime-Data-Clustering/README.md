# 🚔 Crime Data Clustering using K-Means & Hierarchical Clustering

## 📌 Problem Statement
Perform clustering (K-Means and Hierarchical Clustering) on crime data
to identify the number of clusters formed and draw meaningful inferences.

---

## 🎯 Objective
To group different regions of the United States based on similar crime patterns
using unsupervised learning techniques.

---

## 📂 Dataset Description
The dataset contains crime statistics for different places in the United States.

**Features:**
- Murder – Murder rate  
- Assault – Assault rate  
- UrbanPop – Percentage of urban population  
- Rape – Rape rate  

---

## 🧠 Techniques Used
- K-Means Clustering
- Hierarchical Clustering
- Elbow Method
- Dendrogram
- StandardScaler

---

## ⚙️ Steps Performed
1. Loaded crime dataset
2. Removed state/place name column
3. Standardized numerical features
4. Used Elbow Method to determine optimal clusters
5. Applied K-Means clustering
6. Applied Hierarchical clustering
7. Validated clusters using dendrogram
8. Interpreted clustering results

---

## 📊 Results & Inferences
- **Cluster 1:** High crime rate regions → require focused intervention  
- **Cluster 2:** Moderate crime regions → preventive measures needed  
- **Cluster 3:** Urban-dominant regions → urban planning & policing  
- **Cluster 4:** Low crime regions → safer areas  

---

## 💼 Use Cases
- Crime pattern analysis
- Policy planning
- Resource allocation for law enforcement
- Public safety decision-making

---

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Scikit-learn
- SciPy

---

## 📌 Conclusion
Both K-Means and Hierarchical clustering successfully grouped regions into
distinct clusters based on crime statistics, providing valuable insights
for crime prevention and public safety planning.
