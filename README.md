# **Federated Learning for Intrusion Detection in Network Traffic**

## **Overview**
This project explores the **use of Federated Learning (FL) and Deep Learning** for **intrusion detection in network traffic**, with a focus on **privacy-preserving decentralized model training**. By leveraging **Computer Vision techniques**, the project transforms traditional network traffic data into **image representations**, allowing for improved pattern recognition using deep learning models.

## **Key Features**
- **Federated Learning Approach**: Trains models in a decentralized manner, ensuring **data privacy** by keeping sensitive data local.
- **Deep Learning Models**: Utilizes **Multi-Layer Perceptron (MLP), Convolutional Neural Networks (CNN), Deep Neural Networks (DNN), and ResNet** for anomaly detection.
- **Network Traffic Data Processing**: Converts **tabular network data into images**, enhancing the ability to capture intricate attack patterns.
- **Explainable AI (XAI)**: Implements **Saliency Maps, LIME visualizations, and Feature Maps** to interpret model decisions and improve transparency.
- **Performance Evaluation**: Assesses model accuracy, loss, and classification performance in a federated learning setup.

## **Dataset**
The project uses the **NF-ToN-IoT dataset**, a **network traffic dataset** designed for **intrusion detection in IoT environments**. The dataset contains a mix of benign and attack traffic samples, providing a comprehensive testbed for evaluating model performance.

## **Methodology**
1. **Data Preprocessing**:
   - **Convert tabular network traffic data into images** for better feature extraction.
   - **Normalize and encode categorical features** for deep learning compatibility.

2. **Model Training & Evaluation**:
   - Train **MLP, CNN, DNN, and ResNet** models for anomaly detection.
   - Implement **Federated Learning (FL) for distributed model training**.
   - Evaluate models using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**.

3. **Explainability & Interpretability**:
   - Use **Saliency Maps & LIME** to visualize feature importance and model decisions.
   - Analyze the impact of different **network attack types** on model predictions.

## **Results**
- **ResNet** achieved the highest accuracy in a federated learning setup.
- **CNN performed well in detecting spatial patterns in transformed images**.
- **Federated Learning demonstrated effective anomaly detection while preserving data privacy**.
- **XAI methods improved interpretability** and provided insights into model decision-making.

## **Installation & Setup**
### **Prerequisites**
- Python 3.x
- TensorFlow / PyTorch
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn, OpenCV
- MLflow (for model tracking)
- Federated Learning Libraries (PySyft / Flower)

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/ghantahaindavi/Final.git
   cd Final
