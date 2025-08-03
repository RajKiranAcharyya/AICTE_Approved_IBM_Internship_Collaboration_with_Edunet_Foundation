# IBM Internship Collaboration with Edunet Foundation
Predictive Maintenance system using IBM Watsonx.ai AutoAI — detects machine failures (tool wear, overheating, power failure) via real-time sensor data.

# 🛠️ Predictive Maintenance using AI & IBM Cloud (IBM SkillsBuild Internship Project)

This project was developed as part of the **IBM SkillsBuild Internship on AI & Cloud Technologies** conducted by **Edunet Foundation**, in collaboration with **IBM** and **AICTE**. The goal was to build an AI-driven solution to predict equipment failures in industrial machinery using real-time sensor data.

---

## 📌 Problem Statement

Predict potential equipment failures (such as **tool wear**, **overheating**, or **power failure**) before they occur, using sensor data from industrial machines. Early failure detection enables **proactive maintenance**, reducing downtime and operational costs.

---

## 🚀 Solution Overview

The solution leverages **IBM Watsonx.ai's AutoAI** to:
- Build a high-accuracy classification model (Snap Random Forest Classifier)
- Train it using real-world machine sensor data
- Deploy the model using IBM Cloud to enable real-time predictions via a REST API

---

## 🧠 Technologies Used

| Technology          | Purpose                                   |
|---------------------|-------------------------------------------|
| IBM Watsonx.ai AutoAI | Model generation, feature engineering, tuning |
| Snap Random Forest  | Final selected algorithm                  |
| IBM Cloud Deployment | Real-time REST API prediction             |
| Pandas, NumPy       | Data handling (internally by AutoAI)      |
| sklearn.metrics     | Evaluation (accuracy, precision, recall)  |

---

## ⚙️ System Workflow

1. **Data Collection**: Sensor data (temp, torque, speed, tool wear)
2. **Preprocessing**: Cleaning, feature engineering by AutoAI
3. **Model Training**: AutoAI trains + selects best model (99.5% accuracy)
4. **Deployment**: REST API endpoint created via IBM Watson Machine Learning
5. **Prediction**: Real-time prediction of failure type

---

## 🧪 Sample Input (JSON)

```json
{
  "input_data": [
    {
      "fields": [
        "Type",
        "Air temperature [K]",
        "Process temperature [K]",
        "Rotational speed [rpm]",
        "Torque [Nm]",
        "Tool wear [min]"
      ],
      "values": [
        ["M", 298.6, 309.3, 1551, 42.8, 0]
      ]
    }
  ]
}
``` 

## 📊 Model Performance

- **Algorithm Used**: Snap Random Forest Classifier (AutoAI-generated)
- **Cross-Validation Accuracy**: ~99.5%
- **Evaluation Metrics**: Accuracy, F1-score, Precision, Recall (handled by IBM Watsonx.ai AutoAI)
- **Input Features**: 
  - Air Temperature [K]  
  - Process Temperature [K]  
  - Torque [Nm]  
  - Rotational Speed [rpm]  
  - Tool Wear [min]  
  - Machine Type

---

## 💡 Future Scope

- 📡 **IoT Integration**: Real-time sensor streaming using IoT-enabled devices
- 🤖 **Deep Learning Models**: Use LSTM or CNN for improved sequence/time-series modeling
- 🛠️ **Automated Alerting System**: Trigger scheduled maintenance or notifications via API
- 🌍 **Domain Adaptation**: Apply the model to aviation, automotive, and other industries
- 🧠 **Continuous Learning Loop**: Retrain model periodically with new failure data
- 💸 **Cost-Benefit Layer**: Prioritize predictions based on economic impact

---

## 📚 References

- 🔗 [Kaggle Dataset – Machine Predictive Maintenance](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)  
- 🔗 [IBM Watsonx.ai Documentation](https://www.ibm.com/cloud/watsonx-ai)

---

## 📜 Certifications

- ✅ IBM SkillsBuild Internship – *AI & Cloud Technologies*
- ✅ Getting Started with AI – *IBM Credly Badge*
- ✅ Journey to Cloud – *IBM Credly Badge*
- ✅ RAG Lab – *IBM Credly Badge*

(*PPT is also available within the folder*)

---

## 🙌 Acknowledgements

Special thanks to:

- **IBM**  
- **AICTE**  
- **Edunet Foundation**  
- **IBM Watsonx.ai Team**

---

## 🔗 Connect with Me

**Raj Kiran Acharyya**  
*B.Tech CSE, MCKV Institute of Engineering*  
*rajkiranacharyya@gmail.com*  
*9474643821*





