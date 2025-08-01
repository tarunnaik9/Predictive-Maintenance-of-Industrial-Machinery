#  Predictive Maintenance of Industrial Machinery

##  Problem Statement
Industrial machines often face unplanned downtime due to sudden failures like tool wear, overheating, or power issues. This leads to reduced productivity and increased maintenance costs. The goal of this project is to use machine learning to predict such failures in advance using real-time sensor data, enabling proactive maintenance and improving equipment reliability.

---

##  Proposed Solution
We developed a predictive maintenance model using IBM Watson AutoAI, which analyzes machine sensor data (e.g., temperature, torque, rotational speed) to predict failure types before they occur. The system uses a trained classification model deployed via IBM Watson Machine Learning as a REST API, enabling real-time predictions with high accuracy.

---

##  Technologies Used

- IBM Cloud Lite 
- IBM Watson Studio
- IBM AutoAI (No-code model training)
- IBM Watson Machine Learning (Model deployment)
- IBM Cloud Object Storage (Data handling)
- REST API (Model prediction)
- Kaggle Dataset (Sensor data)
- Python (underlying AutoAI & visualization, optional)


---

##  Machine Learning Model

- **Algorithm Used**: Snap Random Forest Classifier (Auto-selected by AutoAI)
- **Model Accuracy**: 99.5%
- **Input Features**:
  - Air temperature
  - Process temperature
  - Rotational speed
  - Torque
  - Tool wear
- **Output**: Predicted failure type or normal operation

---

##  Results

- Successfully predicted multiple types of failures:
  - Power Failure
  - Tool Wear
  - Heat Dissipation
  - No Failure
- Real-time testing using deployed API returned accurate classifications with confidence scores.
- Outputs were visualized using prediction summary tables and pie charts (AutoAI UI).

---

##  How to Use

1. Upload the dataset to IBM Watson Studio.
2. Use IBM AutoAI to build and train the model.
3. Deploy the best model as an online REST API using IBM Watson Machine Learning.
4. Use the API to submit sensor values and receive failure predictions.

---

##  Future Scope

- Real-time integration with IoT sensors
- Alert system for maintenance staff via SMS/email
- Support for multiple types of machinery
- Mobile and web dashboards for monitoring
- Historical log integration for root cause analysis

---

##  Dataset

Kaggle: [Machine Predictive Maintenance Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

---



---

## 📜 License

This project is for academic and educational use. Free to use with attribution.

