# Hybrid Machine Learning Framework for Intelligent Network Intrusion Detection

## 📌 Overview
This project presents a **Hybrid Machine Learning based Intrusion Detection System (IDS)** designed to detect malicious network activities and cyber attacks efficiently. The system combines multiple machine learning algorithms including **Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Random Forest (RF), and Multi-Layer Perceptron (MLP)** to improve detection accuracy and reduce false alarms.

The proposed hybrid ensemble model is trained on the **NSL-KDD dataset** and uses feature selection techniques to enhance performance and reliability in real-world cybersecurity environments.

---

## 🚀 Features
- Detects both **normal and malicious network traffic**
- Supports detection of:
  - DoS (Denial of Service)
  - Probe Attacks
  - R2L (Remote to Local)
  - U2R (User to Root)
- Hybrid ensemble model using multiple ML algorithms
- Feature selection for dimensionality reduction
- High detection accuracy (~99%)
- Reduced false positives and false negatives
- Performance evaluation using multiple metrics

---

## 🛠️ Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

### NSL-KDD Dataset
The project uses the **NSL-KDD dataset**, a widely used benchmark dataset for intrusion detection research.

#### Dataset Details
- Training Records: 125,973
- Testing Records: 22,544
- Features: 41 input features + 1 target label

#### Attack Categories
- DoS
- Probe
- R2L
- U2R

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Removing duplicate records
- Encoding categorical features
- Feature scaling and normalization

### 2. Feature Selection
- Applied Random Forest feature importance
- Reduced irrelevant and redundant features
- Improved model performance

### 3. Model Building
Implemented the following machine learning models:
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest (RF)
- Multi-Layer Perceptron (MLP)

### 4. Hybrid Ensemble Model
- Combined predictions using majority voting
- Improved stability and reliability
- Reduced model errors

---

## 📊 Evaluation Metrics
The model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📈 Results
- Random Forest achieved the highest individual accuracy: **99.56%**
- Hybrid Ensemble Model achieved approximately **99.14% accuracy**
- Reduced false positives and false negatives
- Improved generalization compared to single-model approaches

---

## 🧠 Applications
- Network Security Monitoring
- Intrusion Detection Systems
- Cyber Attack Detection
- Enterprise Network Protection
- Cloud Security Monitoring
- Real-Time Threat Detection

---

## 🔮 Future Enhancements
- Implement Deep Learning models (CNN, LSTM)
- Real-time streaming intrusion detection
- Cloud deployment
- Enhanced zero-day attack detection
- Faster and scalable architecture

---


## ▶️ How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/intrusion-detection-system.git
cd intrusion-detection-system
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open the Project Notebook
Open:
```bash
mainproject.ipynb
```

---



---


## ⭐ Conclusion
This project demonstrates the effectiveness of a hybrid machine learning approach for intrusion detection. By combining multiple classifiers and feature selection techniques, the proposed IDS achieves high accuracy, stability, and reliability suitable for modern cybersecurity applications.
