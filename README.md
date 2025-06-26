# 🧠 HealthAI - Intelligent Disease Predictor

HealthAI is a smart healthcare assistant that predicts possible diseases based on user-input symptoms and provides relevant information such as symptom descriptions, precautions, and severity levels. This offline application is built using Python and machine learning with Gradio for an interactive user interface.

---

## 🚀 Features

- ✅ Predicts disease from symptoms (Naive Bayes model)
- ✅ Describes each symptom with details
- ✅ Suggests home-based precautions
- ✅ Shows severity rating for each symptom
- ✅ Fully offline – no API needed
- ✅ Interactive UI using Gradio

---

## 📊 Datasets Used (from Kaggle)

1. **dataset.csv** – Contains training data with symptoms and related disease labels  
2. **symptom_Description.csv** – Description of each symptom  
3. **symptom_precaution.csv** – Preventive steps to take for each symptom  
4. **Symptom-severity.csv** – Numerical severity weight for each symptom  

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- Gradio (UI Framework)
- Machine Learning – Naive Bayes

---

## 💻 How to Run

1. Clone this repo or upload files to Google Colab
2. Upload the following files to your Colab environment:
   - `dataset.csv`
   - `symptom_Description.csv`
   - `symptom_precaution.csv`
   - `Symptom-severity.csv`
3. Run the `main.py` or Colab notebook
4. Gradio will provide a public URL where you can interact with the app

---

## 🖼️ Sample Screenshot

![HealthAI Screenshot](your_screenshot_image_here)

---

## 📦 Requirements

Install these dependencies before running the project:

```bash
pip install pandas numpy scikit-learn gradio
