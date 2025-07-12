# 🧠 Mouse Movement Anomaly Detection using Isolation Forest

This project uses the **Isolation Forest** algorithm to detect anomalies in simulated mouse movement data. The goal is to identify unusual or suspicious behavior, which could be applied to detecting cheating, fraud, or abnormal user patterns.

---

## 📁 Project Structure

- `clean_mouse_isolation_forest.ipynb`: Main Jupyter Notebook containing:
  - Data simulation
  - Feature extraction (speed & acceleration)
  - Anomaly detection using Isolation Forest
  - Visualizations
  - Summary and export

---

## 📊 Features Used

- `speed`: Calculated from position over time.
- `acceleration`: Change in speed over time.

---

## 🧪 Tools & Libraries

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (IsolationForest)

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells step-by-step.
3. Anomalies will be visualized and saved to `mouse_movement_with_anomalies.csv`.

---

## 📌 Example Output

- Scatter plot showing anomalies (red) vs. normal behavior (blue)
- CSV file with predictions
- Summary of detected anomalies

---

## 💡 Future Work

- Apply on real user mouse movement datasets
- Compare with other anomaly detection algorithms (e.g., One-Class SVM, LOF)
- Use additional features like click frequency, dwell time, etc.

---

## 👩‍💻 Author

**Hiba N. Zalloum**  
MSc in AI & Data Analysis  
📍 Hebron, Palestine  
