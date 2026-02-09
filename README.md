
# Chest X-Ray Pneumonia Detection using Deep Learning

## 📌 Project Overview
This project focuses on detecting **Pneumonia** from **Chest X-Ray images** using **Convolutional Neural Networks (CNNs)**.  
Multiple deep learning models were trained and compared to analyze the effect of **Dropout**, **Batch Normalization**, and their combination on model performance.

The project is intended for **educational and research purposes** and demonstrates an end-to-end deep learning workflow including data preprocessing, model training, evaluation, and comparison.

---

## 🧠 Models Implemented
- **Baseline CNN**
- **CNN with Dropout**
- **CNN with Batch Normalization**
- **CNN with Dropout + Batch Normalization**

Each model was trained and evaluated to study improvements in generalization and accuracy.

---

## 📂 Dataset
The dataset used is the **Chest X-Ray Pneumonia Dataset**, publicly available on **Kaggle**.

🔗 Dataset link:  
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

> ⚠️ **Note:**  
> The dataset is **not included in this repository** due to size constraints. Please download it manually from Kaggle and place it in the required directory structure before running the code.

---

## 🗂️ Dataset Directory Structure
After downloading, organize the dataset as follows:

```

chest_xray/
│
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
└── test/
├── NORMAL/
└── PNEUMONIA/

````

---

## 🛠️ Tools & Technologies
- **Python**
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**
- **OpenCV**

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chest-xray-pneumonia-detection.git
   cd chest-xray-pneumonia-detection
````

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in the project directory.

4. Run the training notebook or script:

   ```bash
   python train.py
   ```

   *(or open the Jupyter Notebook if provided)*

---

## 📊 Results

* Models with **Dropout** showed reduced overfitting.
* **Batch Normalization** improved convergence speed.
* The combination of **Dropout + Batch Normalization** achieved the best overall performance.

(Exact metrics can be found in the training logs / notebooks.)

---

## 📌 Key Learnings

* Impact of regularization techniques in CNNs
* Importance of data preprocessing in medical imaging
* Performance comparison of deep learning architectures

---

## ⚠️ Disclaimer

This project is **not intended for medical diagnosis**. It is purely for learning and research purposes.

---

## 🙌 Acknowledgements

* Kaggle for providing the dataset
* TensorFlow & Keras documentation
* Open-source community

---

## 📬 Contact

If you have any questions or suggestions, feel free to connect!

**Author:** Yash

```
Just say the word 😄
```
