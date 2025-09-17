# Customer Segmentation using K-Means

This project applies **K-Means clustering** on customer purchasing data to group similar customers into segments.

## 📂 Project Structure
- `notebooks/kmeans_customer_clustering.ipynb` → Full code
- `screenshots/elbow_plot.png` → Elbow method visualization
- `screenshots/clusters.png` → Cluster visualization

## 🚀 Steps Implemented
1. Data loading (Mall Customers dataset)
2. Feature selection (`Annual Income`, `Spending Score`)
3. Normalization using StandardScaler
4. Elbow method to determine optimal K
5. K-Means training
6. Visualization of customer segments

## 📊 Results
- Found optimal **K = 5**
- Generated **customer clusters** based on purchasing behavior

## 🛠 Requirements
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
