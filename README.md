🚀 Anomaly-Based Intrusion Detection System (IDS) for IoT Devices

## 📌 Project Overview
This project implements an **Anomaly-Based Intrusion Detection System (IDS)** designed for detecting malicious network activities in IoT environments using Machine Learning / Deep Learning techniques.

The system analyzes network traffic data and classifies it as **Normal** or **Attack** based on learned behavioral patterns.

---

## 🎯 Features
- 📊 Automatic dataset loading and preprocessing  
- 🤖 Deep Learning based anomaly detection  
- ⚡ GPU acceleration support (CUDA)  
- 📉 Model evaluation using multiple metrics  
- 🔍 Real-time detection compatible architecture  
- 📁 Scalable dataset handling  

---

## 🧠 Dataset Used
This project uses the **CICIOT2023 Dataset**, which contains network traffic data for IoT environments including multiple attack categories.

---

## 🛠️ Technologies & Tools

### Programming & Frameworks
- Python
- PyTorch
- Scikit-learn
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

### Environment
- Kaggle / Jupyter Notebook
- GPU Acceleration (Optional)

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Automatically loads multiple CSV files
- Merges them into a single dataset

### 2️⃣ Data Preprocessing
- Label detection
- Feature extraction
- Data normalization using StandardScaler
- Train, Validation, Test splitting

### 3️⃣ Model Training
- Deep Learning model built using PyTorch
- Batch training using DataLoader
- GPU support enabled

### 4️⃣ Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📂 Project Structure

├── notebook.ipynb # Training & Evaluation Notebook
├── model/ # Trained Model Files (if added)
├── scaler/ # Saved Scaler
├── dataset/ # Dataset directory
└── README.md # Project Documentation


---

## 🚀 Installation & Setup

### Step 1: Clone Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run Notebook
jupyter notebook
📊 Model Training
The notebook performs:

Dataset preprocessing

Feature scaling

Dataset splitting

Model training

Performance evaluation

📈 Evaluation Metrics
Accuracy

Precision

Recall

F1 Score

Confusion Matrix

💡 Future Improvements
Real-time packet sniffing integration

Deployment on Raspberry Pi (ARM Architecture)

Explainable AI integration (SHAP / LIME)

Web Dashboard Integration

Multi-model Ensemble IDS

👨‍💻 Author
Muhammad Faizan
Computer Engineering Student
COMSATS University Lahore

📜 License
This project is for academic and research purposes.

