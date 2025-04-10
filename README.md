# 🔐 Performance Analysis of Intrusion Detection in SDN

This project demonstrates the implementation and analysis of an Intrusion Detection System (IDS) in a Software Defined Networking (SDN) environment using machine learning techniques. We used Random Forest Classifier to detect and classify multiple types of network attacks (DoS, Probe, R2L, U2R) and measured its performance using various evaluation metrics.

---

## 📌 Project Highlights

- Simulated SDN network environment
- Performed traffic analysis on CICIDS2019 dataset
- Implemented ML-based IDS with accuracy >90%
- Classified attacks using Random Forest
- Evaluated model using F1-score, confusion matrix, precision, and recall

---

## 💻 Tech Stack

- Python (Jupyter / Kaggle Notebook)
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- CICIDS2019 dataset
- Mininet (for topology testing, optional)

---

## 📂 Dataset

We used **CICIDS2019**, a well-known intrusion detection dataset that contains both benign and malicious traffic for testing IDS systems.

If running on Kaggle, simply upload the dataset and update the path in the notebook accordingly:
```python
file_path = ""/kaggle/input/cicids2019/UDPLag_data_2_0_per.csv""
