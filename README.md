# QR_Code_Authentication
Developed a machine learning model to classify QR codes as original (first print) or counterfeit (second print) using copy detection patterns (CDPs). Leveraging computer vision and deep learning, the model detects distortions from reprinting, aiding in anti-counterfeiting efforts for secure authentication systems.

📌 Project Highlights
🔹 Dataset Preprocessing & Feature Engineering – Cleaned, structured, and optimized data for training.
🔹 Model Training & Evaluation – Implemented and compared four classifiers:

Convolutional Neural Network (CNN) – Achieved 100% accuracy with perfect classification.

Multi-Layer Perceptron (MLP) – Near-perfect performance, 100% precision and recall.

Random Forest (RF) – Slight misclassification but still robust.

Support Vector Machine (SVM) – Lower accuracy due to misclassification of First Print samples.

🔹 Performance Analysis – Used confusion matrices, accuracy scores, and error rates to assess model effectiveness.

🛠️ Technologies Used
✅ Python – NumPy, Pandas, Scikit-Learn, TensorFlow
✅ Data Visualization – Matplotlib, Seaborn
✅ Machine Learning & Deep Learning – SVM, RF, MLP, CNN

📈 Key Findings & Next Steps
✔️ CNN outperformed all models, making it the best choice for classification.
✔️ MLP performed exceptionally well, with zero misclassifications.
✔️ Random Forest had minor errors but remained a strong contender.
✔️ SVM struggled with class separation, requiring further tuning.

🚀 Future Improvements:
🔸 Optimize CNN for real-time deployment
🔸 Improve feature selection for RF and SVM
🔸 Develop an API for seamless classification integration

🔗 Check out the repo for code, results, and insights!
