
# 🌱 DharaaAI – AI-Powered Agricultural Advisory System

DharaaAI is a web-based AI application designed to assist farmers in making **data-driven agricultural decisions**. The system provides intelligent recommendations for **crop selection**, **fertilizer optimization**, and **sustainable crop rotation** based on soil and environmental parameters.

This repository contains the **core source code, configuration files, and documentation** required to understand and run the project. Large datasets, trained models, and environment files are excluded due to GitHub size limitations.

---

## 📌 Problem Statement
Farmers often rely on traditional practices and experience for crop planning and fertilizer usage. These methods may not consider current soil conditions, climate variability, or data-driven insights, leading to reduced yield and inefficient resource usage.

---

## 🎯 Objectives
- Recommend suitable crops using Machine Learning  
- Optimize fertilizer usage based on soil nutrients  
- Promote sustainable crop rotation practices  
- Provide a simple and user-friendly web application  
- Ensure secure user authentication  

---

## 🚀 Key Features
- 🌾 Crop Recommendation using Decision Tree algorithm  
- 🧪 Fertilizer Recommendation using Random Forest algorithm  
- 🔁 Crop Rotation Planning for sustainability  
- 🔐 User Authentication (Login & Registration)  
- 📊 Interactive dashboard for results  

---

## 🧠 Technologies Used
- **Programming Language:** Python  
- **Backend:** Flask / FastAPI  
- **Frontend:** HTML, CSS, JavaScript  
- **Machine Learning:** Scikit-learn  
- **Database:** SQLite / PostgreSQL  
- **Authentication:** JWT (JSON Web Tokens)  
- **Version Control:** Git & GitHub  

---

## 📁 Repository Structure
```
DharaaAI/
├── app.py
├── model/
│   └── model_scripts/
├── dataset/
│   └── sample_data.csv
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
├── static/
│   ├── css/
│   └── js/
├── screenshots/
│   ├── login.png
│   ├── crop_result.png
│   └── fertilizer_result.png
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Execution

### Prerequisites
- Python 3.8+
- pip

### Steps
```bash
git clone https://github.com/your-username/DharaaAI.git
cd DharaaAI
pip install -r requirements.txt
python app.py
```

Open your browser and visit:  
`http://127.0.0.1:5000/`

---

## 📊 Dataset Information
The dataset includes the following parameters:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Soil pH
- Temperature
- Humidity
- Rainfall

**Note:** Full datasets are excluded due to GitHub size limits. A small sample dataset is provided for reference.

---

## 📈 Results & Screenshots

### 🔐 User Authentication
<img width="555" height="507" alt="Screenshot 2026-01-13 160004" src="https://github.com/user-attachments/assets/757d7c6e-33fa-4efb-9e04-bef9bd3d7c46" />
<img width="458" height="357" alt="Screenshot 2026-01-13 160016" src="https://github.com/user-attachments/assets/dddbaeda-1c84-4e66-862e-5a223092c65f" />

### 🌾 Crop Recommendation
<img width="1083" height="277" alt="image" src="https://github.com/user-attachments/assets/a1e9c777-8e09-4ace-8b65-62afbab9b182" />
<img width="1083" height="277" alt="image" src="https://github.com/user-attachments/assets/ba15aa31-caf1-421c-b879-da92658850a5" />
<img width="634" height="294" alt="image" src="https://github.com/user-attachments/assets/e540b57a-26b4-4f07-a045-182806894c03" />



### 🧪 Fertilizer Recommendation
![Fertilizer Recommendation Result](screenshots/fertilizer_result.png)

---

## 📝 Note on Large Files
Due to GitHub’s 25 MB file size limit, the following are **not included**:
- Full datasets  
- Trained ML model files (`.pkl`)  
- Virtual environment folders (`venv/`)  

Models can be retrained using the provided dataset structure.

---

## 🔮 Future Scope
- Real-time weather API integration  
- Mobile application support  
- Multilingual interface  
- Advanced ML / Deep Learning models  
- Market price prediction  

---

## 📌 Conclusion
DharaaAI bridges the gap between traditional farming and modern AI-driven agriculture by providing accurate, data-backed recommendations that improve productivity and promote sustainable farming practices.

---

## 👩‍💻 Authors
- **Sanjana K S**  
- Chethana Keshava Shettigar  
- Dyna Pemmaiah K  
- Shashmitha V  

Department of Artificial Intelligence & Data Science  
Srinivas Institute of Technology, Mangaluru

---

## 📜 License
This project is licensed under the **MIT License**.
