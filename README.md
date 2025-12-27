# 🩺 Skin Cancer Detection with Deep Learning (ResNet50)

## 📌 Project Overview
Early detection of melanoma is critical for patient survival. This project utilizes **Transfer Learning** with a pre-trained **ResNet50** neural network to classify skin lesions from the **HAM10000** dataset (Human Against Machine).

The model distinguishes between 7 types of skin lesions, including Melanoma (MEL), Basal Cell Carcinoma (BCC), and Benign Nevi (NV).

## 🧠 Business Value
* **Scalability:** Automates the screening of dermatological images.
* **Accuracy:** Achieved **87% weighted F1-score** on the test set, providing a reliable second opinion for clinicians.
* **Efficiency:** Uses Transfer Learning to reach high accuracy in just 5 epochs of training.

## 🛠️ Tech Stack
* **Deep Learning:** PyTorch (ResNet50 Architecture)
* **Data Processing:** Pandas, NumPy, Torchvision
* **Optimization:** Adam Optimizer, CrossEntropyLoss
* **Infrastructure:** Google Colab (GPU-accelerated training)

## 📊 Key Results
* **Training Loss:** Reduced from **0.84** to **0.55** over 5 epochs.
* **Model Confidence:** Increased prediction confidence from ~18% (random) to **54%+** after fine-tuning.
* **Evaluation:** The model demonstrates robust performance across classes, with high recall (0.90) for benign cases.

## 📂 How to Run
1.  Click the **"Open in Colab"** badge above.
2.  You will need a Kaggle API key (`kaggle.json`).
3.  Run the cells to download the 5GB dataset directly into the cloud environment.
4.  Execute the training loop to fine-tune the model.

## 🔮 Future Work
* Implement **Data Augmentation** (Rotation/Flipping) to further improve robustness.
* Deploy as a web application using **Streamlit**.

---
### ⚠️ Disclaimer
**This project is for educational purposes only.** Artificial Intelligence should never replace professional medical advice. Remember to always discuss any skin conditions with a certified doctor!
