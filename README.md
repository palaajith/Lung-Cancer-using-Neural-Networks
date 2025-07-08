# 🧠 A Novel Hybrid Deep Learning Method for Early Detection of Lung Cancer using Neural Networks

## 📌 Project Overview
This project proposes a **hybrid deep learning model (CCDC-HNN)** combining **3D Convolutional Neural Networks (3D-CNN)** and **Long Short-Term Memory (LSTM)** networks for early-stage lung cancer detection from **CT scan images**. The system leverages **U-Net** for tumor segmentation and classifies the output into **benign or malignant** tumors.

---

## 🧪 Domain
**Artificial Intelligence in Medical Imaging**  
Focused on applying **deep learning** to automate and improve early diagnosis of lung cancer — one of the leading causes of cancer-related deaths globally.

---

## 🎯 Objectives
- Develop a hybrid deep learning model (CCDC-HNN) for early lung cancer detection.
- Accurately segment tumor regions and classify cancer type.
- Reduce manual diagnosis time and improve reliability.

---

## 🔬 System Architecture
1. **Dataset Upload** (LIDC-IDRI)
2. **Preprocessing** (Resizing, Normalization)
3. **Tumor Segmentation** using **U-Net**
4. **Model Training** using **3D-CNN + LSTM**
5. **Prediction and Classification**
6. **Performance Evaluation**

---

## 📚 Literature Review
- Traditional image processing lacks accuracy in medical diagnostics.
- 2D CNNs struggle with temporal sequence understanding.
- Hybrid models combining 3D-CNNs and RNNs offer superior accuracy and early detection capabilities.

---

## ⚙️ Technologies Used
- **Language**: Python 3.7
- **Libraries**: TensorFlow / Keras, OpenCV, Matplotlib
- **Hardware**: Intel i3+, 8GB RAM, 40GB HDD
- **OS**: Windows 10+

---

## 📁 Modules
- Upload and process CT scan dataset
- Tumor segmentation using **U-Net**
- Hybrid classification using **CCDC-HNN**
- Output visualization and performance metrics

---

## 📊 Results
- High accuracy in early-stage lung cancer detection.
- Clear tumor segmentation and classification.
- Confusion matrix and accuracy/loss graphs demonstrate strong model performance.

---

## ⚠️ Limitations
- Computationally intensive
- Dataset-limited to LIDC-IDRI only

---

## 🚀 Future Scope
- Extend to other imaging types (MRI, PET)
- Real-time clinical deployment
- Improve segmentation accuracy with advanced models

---

## 👨‍💻 Team Members
- **Thirupathigari Harshitha** - 22H51A7C0  
- **Chilakani Mahesh Babu** - 23H51A7304  
- **Pala Ajith** - 23H51A7309  

Under the guidance of **Dr. T. Bhaskar**, Assistant Professor, Dept. of CSE (AI & ML), CMRCET.

---

## 📚 References
- LIDC-IDRI Dataset  
- Ronneberger et al., “U-Net: Biomedical Image Segmentation,” 2015  
- Goodfellow, Bengio, Courville, “Deep Learning,” MIT Press, 2016  
- TensorFlow & PyTorch Official Docs  
