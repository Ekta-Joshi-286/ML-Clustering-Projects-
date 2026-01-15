# ✈️ Airlines Customer Segmentation using Clustering

## 📌 Problem Statement
Perform clustering (K-Means and Hierarchical Clustering) on airline frequent flyer data
to obtain the optimum number of clusters and draw meaningful inferences from the clusters obtained.

---

## 🎯 Objective
To segment airline customers based on their mileage history, flight activity, and reward usage,
so that the airline can design targeted mileage offers and loyalty programs.

---

## 📂 Dataset Description
The dataset contains information about passengers enrolled in the airline’s frequent flyer program.

**Features:**
- Balance – Miles eligible for award travel  
- Qual_mile – Qualifying miles for frequent flyer status  
- cc1_miles, cc2_miles, cc3_miles – Credit card miles earned  
- Bonus_miles – Non-flight bonus miles  
- Bonus_trans – Bonus transactions  
- Flight_miles_12mo – Flight miles in last 12 months  
- Flight_trans_12 – Flight transactions in last 12 months  
- Days_since_enrolled – Days since enrollment  
- Award – Award flight usage  

---

## 🧠 Techniques Used
- K-Means Clustering
- Hierarchical Clustering
- Elbow Method
- Dendrogram
- StandardScaler

---

## ⚙️ Steps Performed
1. Loaded airline data from the correct Excel sheet (`dta`)
2. Dropped unique customer ID
3. Standardized the data
4. Used Elbow Method to find optimal clusters
5. Applied K-Means clustering
6. Applied Hierarchical clustering
7. Interpreted clusters and drew business insights

---

## 📊 Results & Inferences
- **Cluster 1:** High-value frequent flyers → premium offers & upgrades  
- **Cluster 2:** Medium engagement customers → bonus mile promotions  
- **Cluster 3:** Low engagement customers → reactivation campaigns  

---

## 💼 Business Use Case
Customer segmentation helps airlines:
- Improve customer retention
- Design targeted loyalty programs
- Increase customer lifetime value

---

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Scikit-learn
- SciPy

---

## 📌 Conclusion
Using clustering techniques, airline customers were successfully grouped into
distinct segments based on travel and reward behavior, enabling data-driven
decision-making for personalized marketing.
