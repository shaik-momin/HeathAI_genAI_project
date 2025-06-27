# 🧠 HealthAI: Intelligent Medical Assistant using Gradio & Hugging Face

**HealthAI** is a smart, lightweight, and interactive AI healthcare assistant built using **Gradio** and **Hugging Face Transformers**.  
It empowers users to interact with an AI-powered medical chatbot, predict diseases based on symptoms, and receive basic treatment suggestions — all inside a single app, hosted on **Google Colab**.

---

## 📽️ Demo Video  
👉 https://drive.google.com/file/d/1--FoyidDkLsffsiXvU2B2jcu3AZGFfm_/view?usp=drivesdk

---

## 🔍 Project Overview

In many rural or underserved areas, quick access to basic medical advice is still a challenge.  
**HealthAI** was developed to bridge that gap using modern AI models and open-source tools.

This project uses:
- A **lightweight language model** (like `flan-t5-base`) to simulate basic medical interaction
- A **rule-based logic** for quick disease prediction
- A **LLM-backed treatment suggestion system**
- A clean and simple **Gradio UI**, runnable directly in the browser

---

## 🚀 Key Features

| Feature | Description |
|--------|-------------|
| 🧠 AI Medical Chatbot | Talk to an AI-powered virtual doctor |
| 🔎 Symptom-based Diagnosis | Enter symptoms and get a possible diagnosis |
| 💊 Treatment Planner | Receive AI-generated treatment suggestions |
| 📈 Lightweight & Fast | Runs in Colab using light LLMs (good for limited compute) |
| ☁️ No Deployment Needed | Can be launched instantly with `gradio.launch()` |

---

## 🧑‍💻 Technologies Used

- **Python** 🐍  
- **Gradio** – for interactive web UI  
- **Hugging Face Transformers** – for LLMs and text generation  
- **Google Colab** – runtime and development environment  
- **Pandas**, **Scikit-learn** – (for optional ML and data handling)


---

## ⚙️ How to Run in Google Colab

1. Open the Colab notebook: `HealthAI_Colab.ipynb`
2. Install dependencies:
    ```python
    !pip install gradio transformers pandas scikit-learn
    ```
3. Paste your Hugging Face token:
    ```python
    import os
    os.environ["HUGGINGFACEHUB_API_TOKEN"] = "your_token_here"
    ```
4. Launch the app:
    ```python
    demo.launch(share=True)
    ```

---

## 🌱 Future Improvements

- ✅ Add real ML model for symptom-based prediction  
- ✅ Visualize health metrics with Plotly charts  
- ⏳ Patient report upload & PDF download  
- ⏳ User authentication system  
- ⏳ Deploy to Hugging Face Spaces or Streamlit Cloud

---

## 📄 License

This project is licensed under the MIT License.  
You are free to reuse, modify, and distribute with credits.

---

## 🙌 Acknowledgements

- [Hugging Face](https://huggingface.co/) for providing open-source LLMs  
- [Gradio](https://gradio.app/) for making AI UI simple  
- Built by **Shaik Momin** ([@mominshaik24](https://github.com/mominshaik))

---

## 📬 Contact

For collaborations or suggestions:  
📧 Email: mominshaik801@gmail.com  
📱 LinkedIn: linkedin/mominshaik

---

