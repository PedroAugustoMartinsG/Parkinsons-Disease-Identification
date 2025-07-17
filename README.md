

# 🧠 Detecting Parkinson’s Disease with AI

Can we detect Parkinson’s Disease *before* motor symptoms become severe?
Our project says yes — with the help of **machine learning and deep learning**.

Developed as part of an undergraduate course at the **Institute of Mathematics and Computer Science (ICMC)** – **University of São Paulo (USP)**, this project explores AI-based approaches to classify **hand-drawn spirals and sine waves** from healthy individuals and Parkinson’s patients.

## ⚙️ Methodology

We explored two main strategies:

1. **Feature Extraction + Traditional Models**

   * Visual descriptors: *Centroid*, *Entropy*, *HOG*, *LBP*
   * Classifiers: *SVM*, *Random Forest*, *XGBoost*

2. **End-to-End Deep Learning**

   * Model: **YOLOv11n-cls** – a state-of-the-art convolutional neural network (CNN) architecture for image classification

## 📊 Key Results

* 🧪 **SVM + PCA** (binary classification): **82.7% accuracy**
* ⚡ **YOLOv11n-cls**: **Up to 92.9% accuracy** with only 30 minutes of training on modest hardware
* ✅ YOLO showed **strong resistance to false negatives** — crucial in medical diagnostics

## 🧾 Conclusion

Despite higher computational requirements, **deep learning significantly improves accuracy** and holds real-world potential for **non-invasive, early detection** of Parkinson’s Disease.
