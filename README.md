# AI-Based Pothole Detection with MLOps Pipeline 
---
## Overview 🚧
This project focuses on developing and deploying an **AI-based pothole detection system** using Convolutional Neural Networks (CNNs) integrated with a robust MLOps pipeline. The solution aims to enhance road safety by automatically identifying potholes from images and streamlining the deployment process through **CI/CD workflows, Airflow pipelines, and automated retraining**.

The project was conducted as part of the **MachineMinds team collaboration**, involving end-to-end experimentation, data management, and deployment.

---

## Objectives
- **Develop a CNN model** capable of detecting potholes with high accuracy.  
- **Integrate MLOps practices** including CI/CD, automated testing, and deployment.  
- **Automate workflows** using Apache Airflow and GitHub Actions.  
- **Enable scalability** through containerization (Docker) and monitoring tools.  
- **Facilitate collaboration** using Jira, Confluence, and ClearML for tracking experiments.  

---

## Methodology
1. **Data Collection & Preprocessing**
   - Road image dataset processed with augmentation (rotation, scaling, normalization).
   - Data validated for quality and consistency across experiments.

2. **Model Development**
   - Implemented CNN for pothole classification.
   - Hyperparameter tuning, cross-validation, and A/B testing for optimization.
   - Achieved **95% accuracy** on test dataset.

3. **MLOps Pipeline**
   - Automated pipelines using **Apache Airflow** for data flow and retraining.
   - CI/CD integration with **GitHub Actions** for model testing & deployment.
   - Docker containerization for cross-environment deployment.
   - ClearML used for experiment tracking and workflow management.

4. **Deployment & Monitoring**
   - Automated triggers for retraining on new data or degraded performance.
   - Monitoring tools to track precision, recall, and model drift in production.

---

## Results
The CNN-based pothole detection system achieved **95% test accuracy** with high recall, ensuring robust detection of potholes in diverse road conditions.

| Metric        | Value |
|---------------|-------|
| Accuracy      | 95%   |
| Precision     | 93%   |
| Recall        | 96%   |
| F1-Score      | 94%   |

These results validate the effectiveness of the model and the scalability of the MLOps pipeline for real-world deployment.

---

## Repository Structure

├── data/ # Datasets and preprocessing scripts
├── notebooks/ # CNN training & evaluation notebooks
├── pipelines/ # Airflow pipelines for automation
├── tasks/ # Individual ML & preprocessing tasks
├── results/ # Metrics, reports, and visualizations
├── docs/ # Reports, slides, and progress updates
└── README.md # Project overview

---
## Tools & Technologies
- **Deep Learning:** CNN, TensorFlow/Keras, PyTorch  
- **MLOps:** Apache Airflow, GitHub Actions, Docker, ClearML  
- **Collaboration:** Jira, Confluence  
- **Version Control:** GitHub (CI/CD integrated)  

---

## Contributors
- **Sarah Altalhi** – *Data Scientist*  
  - Led data preprocessing, CNN model development, and experimental analysis.  
  - Monitored environment setup, and scalability testing.  

- **Choonsik [Role: Project Manager/ MLOps Engineer]**  
  - Implemented Airflow pipelines, CI/CD workflows, and containerization.
  - Oversaw Jira/Confluence documentation, sprint planning, and task allocation.

- **Tran [Role: DevOps Engineer]**  
  - Managed the deployment environment.
  - Designed automated retraining strategies and contributed to MLOps integration.

