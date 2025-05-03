 Anomaly Detection using Deep Learning
📌 Overview
This project implements anomaly detection using deep learning and machine learning algorithms to identify unusual patterns in datasets. Our approach outperforms existing IoT anomaly detection models with higher accuracy and low false positives.

✨ Key Features
✅ State-of-the-art accuracy (99.96% with Decision Tree, 99.87% with MLP)
✅ Advanced deep learning techniques (Hyperparameter tuning & oversampling)
✅ Dataset preprocessing & feature engineering for better model performance
✅ Comparison with existing research to showcase superior results

📊 Dataset Information
Source: Kaggle - DS2OS Traffic Traces
Context: Captured IoT traffic traces to address the lack of publicly available datasets.
Total Records: 357,952 IoT network interactions
Number of Columns: 13 (Including source, destination, timestamps, and operation types)

🔍 Use Case
This dataset is used for IoT anomaly detection, security threat analysis, and understanding concept drift in smart environments.

🏆 Model Performance
Our models achieve higher accuracy than existing IoT anomaly detection techniques.

🔥 Accuracy Comparison
Algorithm	Accuracy
🏆 Decision Tree	99.96%
🎯 Multilayer Perceptron (MLP)	99.87%
🌲 Random Forest	98.97%
📊 SVM	85.42%
🔍 KNN	88.05%
📈 Logistic Regression	81.91%
🔬 Training Results
Optimizer	Epochs	Training Accuracy	Testing Accuracy	Training Loss	Testing Loss
🛠 Adam	10	98.53%	99.87%	0.0523	0.0070
🛠 Adam	15	98.35%	99.74%	0.0594	0.0093
⚡ RMSprop	10	98.23%	99.80%	0.0771	0.0103
⚡ RMSprop	15	98.43%	99.77%	0.0846	0.0136
📊 Comparison with State-of-the-Art Research
Our results outperform a widely recognized IoT anomaly detection research paper:

📜 "All Eyes on You: Distributed Multi-Dimensional IoT Microservice Anomaly Detection" reports 99% accuracy with a false positive rate of 0.2% and detection rate of 96.3%.
🔥 Our Multilayer Perceptron (MLP) achieves 99.87% accuracy, outperforming their model.
🏆 Our Decision Tree model achieves 99.96% accuracy, making it one of the best in anomaly detection.
This highlights the effectiveness of our deep learning-based approach.# anomaly-detection-DS20S
