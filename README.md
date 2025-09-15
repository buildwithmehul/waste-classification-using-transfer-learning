# 🗑️ Waste Classification using Deep Learning (VGG16 + Transfer Learning)

### ♻️ Organic vs Recyclable Waste Classifier  
A deep learning project built with **TensorFlow & Keras**, using **Transfer Learning (VGG16)** to classify waste images into **Recyclable** and **Organic** categories.  

This project was developed as the **final capstone** of my *Deep Learning with Keras & TensorFlow* course.  

---

## 🚀 Project Overview
Waste management is a growing challenge in modern cities. Manual sorting is:  
- ❌ Time-consuming  
- ❌ Error-prone  
- ❌ Resource-intensive  

This project leverages **AI-powered image recognition** to automate waste classification, improving recycling efficiency and reducing contamination.  

✅ **Input:** Waste image (e.g., food, bottles, paper)  
✅ **Output:** `Organic 🌱` or `Recyclable ♻️`  

---

## 🔑 Key Features
- 📸 Image preprocessing & augmentation  
- 🧠 Transfer Learning with **VGG16**  
- 🎯 Fine-tuning for improved accuracy  
- 📊 Training & validation performance visualization  
- 🔍 Test image predictions  

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- **TensorFlow / Keras**  
- **Matplotlib & Seaborn** (visualization)  
- **NumPy & Pandas** (data handling)  
- **Google Colab / Jupyter Notebook**  

---

## 📂 Project Structure
```bash
├── Final Proj-Classify Waste Products Using TL- FT-completed.ipynb         # Main notebook             
├── o-vs-r-split/                                                           # Dataset
│   └── train
│   │   └── O
│   │   └── R
│   └── test
│       └── O
│       └── R
├──  README.md                                                   # Project documentation
├──  requirements.txt                                            # Requirements 
└── .gitignore                                                   # Ignore big files & venv
```

---

## 🚀 How to Run

1. Clone the repo:
```bash
    git clone https://github.com/buildwithmehul/waste-classification-using-transfer-learning.git
    cd waste-classification-using-transfer-learning
```
2. Create a virtual environment & install dependencies
```bash
    python -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows

    pip install -r requirements.txt
```
3. Open the notebook:
```bash
    jupyter notebook notebooks/Final\ Proj-Classify\ Waste\ Products\ Using\ TL-FT-v1.ipynb
```
4. Run all cells to train/evaluate the model.

---

## 📊 Workflow
1. Load dataset and preprocess images.  
2. Apply transfer learning using pre-trained CNNs (e.g., MobileNet, ResNet).  
3. Fine-tune model layers for better feature extraction.  
4. Train and evaluate model performance.  
5. Save trained model for deployment.

---

## 📊 Results & Visuals

Accuracy / Loss Curves
<img width="679" height="506" alt="image" src="https://github.com/user-attachments/assets/f0312359-1113-4ad0-81b4-8a4cc004ef88" />

Example Prediction

Input Image: 🍌 banana peel
Model Output: ```Organic 🌱```

Input Image: 🥤 plastic bottle
Model Output: ```Recyclable ♻️```

---

## 💡 Future Improvements

- Extend to more waste categories (metal, glass, paper, plastic)
- Deploy as a web app with Streamlit / Flask
- Optimize inference for edge devices (e.g., Raspberry Pi in smart bins)

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit PRs.

---

## ✨ Acknowledgements

- VGG16 Pre-trained Model (ImageNet)
- Course: Deep Learning with Keras & TensorFlow
- Inspiration: Real-world need for sustainable waste management

---

## 🎓 Certificate
![Deep Learning with Keras and Tensorflow_page-0001](https://github.com/user-attachments/assets/604cf7e1-9375-4778-81ea-f8373dd8d23b)

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

