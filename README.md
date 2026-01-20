# Assistive Brain Hemorrhage Detection for Early Diagnosis 🧠

**Status:** Ongoing (Oct 2025 – June 2026)   
**Institution:** Namal University, Mianwali
**Supervised by:** Proff. Zulaikha Kiran and Dr. Farrukh Qureshi

## 📝 Abstract
This project focuses on the development of an AI-supported detection system to identify brain hemorrhages from Non-Contrast CT (NCCT) scans and classify their subtypes. Addressing the critical shortage of radiologists in Pakistan's public hospitals, this system aims to reduce diagnosis delays and prevent data loss through a centralized local server solution.

## 🎯 Project Goals
1. **Binary Classification:** Detect the presence of hemorrhage (Normal vs. Abnormal).
2. **Subtype Classification:** Identify the specific type of hemorrhage (e.g., Intracranial, Subdural).
3. **Deployment:** Provide a user-friendly Web Interface for doctors using **Streamlit**.
4. **Data Management:** Implement a local server solution to address the lack of PACS in rural hospitals.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** PyTorch / TensorFlow / Keras
* **Computer Vision:** OpenCV
* **Data Processing:** Pandas, NumPy, Scikit-learn
* **Web Interface:** Streamlit, FastAPI
* **Hardware:** Trained on High-Performance Computing (HPC) GPU resources[cite: 732].

## 📊 Methodology
The project follows a hybrid deep learning approach:
1. **Data Collection:** Collaboration with DHQ Hospital Mianwali to collect ~4,800 DICOM images (Hemorrhage & Healthy).
2. **Preprocessing:** Anonymization, Normalization, and Resizing of DICOM files.
3. **Annotation:** Expert labelling by radiologists to mark hemorrhage regions and subtypes.
4. **Model Architecture:** A Hybrid CNN (for feature extraction) combined with lightweight classifiers (ANN/SVM) for classification.
5. **Evaluation Metrics:** Sensitivity, Specificity, Precision, F1 Score, and AUC.

## 👥 Team Members
* **Uzair Bilal** (Lead: Preprocessing, Training, Deployment)
* **Muskan Aman Khan** (Lead: Data Collection, Annotation, Testing) 

## 🤝 Collaboration
This research is conducted in collaboration with the **Department of Diagnostic Imaging, DHQ Hospital Mianwali**.
