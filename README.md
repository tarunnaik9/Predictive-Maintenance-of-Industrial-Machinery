#  Predictive Maintenance of Industrial Machinery

##  Problem Statement
A predictive maintenance model for a fleet of industrial machines to anticipate 
failures before they occur. This project will involve analyzing sensor data from machinery 
to identify patterns that precede a failure. The goal is to create a classification model that 
can predict the type of failure (e.g., tool wear, heat dissipation, power failure) based on 
real-time operational data. This will enable proactive maintenance, reducing downtime 
and operational costs. 

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

