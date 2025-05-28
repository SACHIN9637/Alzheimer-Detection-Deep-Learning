# 🧠 Alzheimer's Disease Detection using Multimodal Deep Learning

This project implements a multimodal deep learning model to classify Alzheimer's Disease (AD) using both **MRI brain scans** and **structured clinical data**. The model combines the strengths of **MobileNetV2** (for image feature extraction) and a **Multilayer Perceptron (MLP)** (for tabular data), integrating both via intermediate fusion for robust prediction.

## 📌 Project Highlights

- 🔬 Uses MRI scans + clinical biomarkers
- 🤖 MobileNetV2 for image processing
- 🧮 MLP for structured data analysis
- 🔗 Intermediate fusion of features
- ✅ Achieves **95% accuracy**
- 📊 Confusion matrix & metric visualization

---

## 🗂️ Files

- `Alzheimer's_Detection.ipynb` – Main notebook implementing the model
- `README.md` – Project overview and usage
- `requirements.txt` – Python dependencies (to be added if needed)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/alzheimer-multimodal-diagnosis.git
cd alzheimer-multimodal-diagnosis
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is missing, install manually:
```bash
pip install tensorflow pandas numpy matplotlib scikit-learn opencv-python
```

### 4. Run the Notebook

Use Jupyter Lab or Notebook:

```bash
jupyter notebook Alzheimer's_Detection.ipynb
```

---

## 📊 Dataset Used

- **MRI Dataset:** Preprocessed 2D brain scans
- **Tabular Data:** Age, MMSE, gender, etc.

> You can use open datasets like [OASIS-3]([https://www.oasis-brains.org/](https://www.kaggle.com/datasets/lukechugh/best-alzheimer-mri-dataset-99-accuracy?resource=download)) or simulate with dummy data for testing.

---

## 📈 Results

| Metric     | Value |
|------------|-------|
| Accuracy   | 95%   |
| Precision  | 0.87  |
| Recall     | 0.88  |
| F1-Score   | 0.87  |

---

## 💡 Future Work

- Attention-based fusion
- Multi-class classification (e.g., MCI stages)
- Real-time inference pipeline
- Integration with clinical software (FHIR API, etc.)

---

## 👨‍💻 Authors

- Sachin Jadhav
- Khushi Narad  
- Shivanjali Jagtap  
- Diptee Ghusse  
- Sunita S. Barve

Department of Computer Engineering, MITAOE

---

## 📜 License

This project is for academic and research purposes. For commercial use, please contact the authors.
