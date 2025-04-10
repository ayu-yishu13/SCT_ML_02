# 🧠 Mall Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers based on their **Annual Income** and **Spending Score** using the Mall Customer Dataset. It helps identify customer groups for targeted marketing strategies.

---

## 📁 Project Structure
SCT_ML_02_KMeans_Clustering/ │ ├── data/ # Contains the original dataset ├── models/ # Saved trained KMeans model ├── outputs/ # Clustered results (CSV), plots (optional) ├── SCT_ML_02_KMeans.ipynb # Main notebook └── README.md # This file


---

## 📊 Dataset Overview

- **Source**: Mall Customer Dataset
- **Features**:
  - `CustomerID` (dropped for modeling)
  - `Gender` (encoded)
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## ⚙️ Technologies Used

- Python 3
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook
- Git & GitHub

---

## 🔍 Approach

1. **Data Preprocessing**:
   - Dropped `CustomerID`
   - Label encoded `Gender`
   - Scaled features using `StandardScaler`

2. **Elbow Method**:
   - Used WCSS to determine optimal clusters
   - Selected **k = 5**

3. **Model Training**:
   - KMeans clustering from scikit-learn
   - Cluster labels added to dataset

4. **Visualization**:
   - 2D scatterplot of `Annual Income vs Spending Score` colored by cluster

5. **Model Saving**:
   - Trained model saved to `models/kmeans_model.pkl` for reuse

---

## 🧠 Insights

- Customers were segmented into 5 distinct groups
- Visual inspection helps identify high-income, low-spending or low-income, high-spending customers
- Ideal for targeted marketing campaigns

---

📌 Author
Ayush Rai
AI & ML Enthusiast | Strategist in Code and Life 🧠⚔️

  
  ---


##pictures
![Screenshot (60)](https://github.com/user-attachments/assets/ba94c6fa-674b-46a1-a132-55d39028b147)
![Screenshot (59)](https://github.com/user-attachments/assets/08f72adc-e726-4149-ba35-9b922d6679fa)
![Screenshot (58)](https://github.com/user-attachments/assets/dc7a0658-77a8-4be5-8529-054b65bc5a9b)
![Screenshot (57)](https://github.com/user-attachments/assets/1aeb18f1-6ce8-48d7-a663-c3b2537a6444)
![Screenshot (56)](https://github.com/user-attachments/assets/91ae6d42-6b3e-4e70-b9e0-31a882a7db6f)
![Screenshot (55)](https://github.com/user-attachments/assets/954542a9-8a76-4448-b77a-0578edac9fdd)

  ---
## 💾 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/YourUsername/SCT_ML_02_KMeans_Clustering.git

