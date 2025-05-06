![image](https://github.com/user-attachments/assets/91c7e11c-7892-4ec1-81ec-5c44d65170ee)# Intrusion Detection Using Machine Learning

This project implements a machine learning-based Intrusion Detection System (IDS) using a Jupyter notebook in Google Colab. It aims to detect malicious activity in network traffic through supervised learning models. The approach includes preprocessing, model training, evaluation, and visualization of results.

📁 File: `IntrusionDetection.ipynb`

---

## 📌 Features

- Dataset loading and preprocessing
- Feature selection and normalization
- Training classification models (e.g., Random Forest, Decision Tree, SVM)
- Evaluation using accuracy, confusion matrix, and classification report
- Results visualization

---

## 🔧 Requirements

This project is designed to run in Google Colab, which already includes most dependencies. If running locally, install the following:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## 🚀 Getting Started

1. Clone this repository or download the notebook file:

```bash
git clone https://github.com/YOUR_USERNAME/intrusion-detection-ml.git
```
2. Open the Notebook
- Google Colab (Recommended):
- Or open locally using Jupyter Notebook or VS Code.

3. Run the Notebook
Run each cell in order to:
- Load and preprocess the dataset
- Train machine learning models
- Evaluate and visualize results

##🧰 Requirements
The notebook runs best in Google Colab. If running locally, install the following:
```bash
pip install pandas scikit-learn matplotlib seaborn

```
## 📊 Models Used
- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machine (SVM)
Feel free to extend the notebook with additional models such as KNN, XGBoost, or deep learning techniques.

## 📂 Dataset
Make sure the dataset file used in the notebook is uploaded when prompted in Colab.

If using a public dataset (e.g., UNSW-NB15 or CICIDS2017), download the dataset separately and update the notebook's file path:
```bash
df = pd.read_csv('/content/your_dataset.csv')
```
##📈 Evaluation Metrics
The notebook evaluates models using:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

Visualizations are provided using seaborn and matplotlib for better interpretability.

## 🛠️ Customization
You can easily modify the notebook to:

- Add or remove classification models
- Change feature selection techniques
- Tune model hyperparameters
- Add cross-validation or grid search
- Visualize more metrics

👩‍💻 Authors : 
Arwa Alomari
Hassan Alsayed
Mohamed Albarazi


