
# 🧠 Kidney Tumor Prediction – End-to-End MLOps Project

This project focuses on predicting kidney tumors using a machine learning pipeline that follows full MLOps best practices. It is trained, tracked, versioned, containerized, deployed, and automated using industry-standard tools.

## 🔗 Live Demo
Access the deployed model here: [Kidney Tumor Prediction App](http://ec2-13-127-72-220.ap-south-1.compute.amazonaws.com:8080/)

## 📂 GitHub Repository
Source code and documentation: [GitHub - Kidney_Tumor_Prediction](https://github.com/shreeyanshm/Kidney_Tumor_Prediction)

---

## 🚀 Features

- 📊 Model training and evaluation with Scikit-learn
- 🔁 Experiment tracking using **MLflow**
- 📦 Data and model versioning using **DVC**
- 🐳 Containerized with **Docker**
- ☁️ Deployed on **AWS EC2**
- 🔁 Automated CI/CD with **GitHub Actions**
- ⚡ FastAPI for backend inference
- 📉 Real-time tumor prediction on structured medical data

---

## 🏗️ Tech Stack

| Layer         | Tool/Library            |
|---------------|--------------------------|
| ML Framework  | Scikit-learn             |
| Experiment Tracking | MLflow             |
| Data Versioning | DVC                    |
| API Framework  | FastAPI                 |
| Containerization | Docker                |
| Cloud Platform | AWS EC2                 |
| CI/CD         | GitHub Actions           |

---

## 📁 Project Structure

```
Kidney_Tumor_Prediction/
│
├── data/                   # Dataset files (DVC tracked)
├── models/                 # Saved models (MLflow registered)
├── app/                    # FastAPI app files
├── src/                    # Training, preprocessing scripts
├── Dockerfile              # Container setup
├── requirements.txt        # Dependencies
├── .dvc/                   # DVC config and pipelines
└── README.md               # Project documentation
```

---

## ✅ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/shreeyanshm/Kidney_Tumor_Prediction.git
   cd Kidney_Tumor_Prediction
   ```

2. Start Docker:
   ```bash
   docker build -t kidney-tumor-app .
   docker run -p 8080:8080 kidney-tumor-app
   ```

3. Access the app:
   [http://localhost:8080](http://localhost:8080)

---

## 📬 Contact

Created by [Shreeyansh Mittal](https://github.com/shreeyanshm) – feel free to reach out!

---

## 🏁 Acknowledgements

- UCI & Kaggle for medical datasets
- MLflow, DVC, Docker, AWS – for enabling MLOps at scale
