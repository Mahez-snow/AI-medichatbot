# healthcare_chatbot_AI
#  NovaCure-AI | AI-Powered Medical Assistant 🤖✨

NovaCure-AI is an intelligent healthcare chatbot that integrates **Machine Learning**, **Natural Language Processing**, and **Generative AI** to provide structured medical insights through an interactive web interface.

🔗 Live Application: [(https://ai-medichatbot.streamlit.app/)(https://ai-medichatbot.streamlit.app/)]

📂 GitHub Repository: [(https://github.com/Mahez-snow/AI-medichatbot/tree/main)](https://github.com/Mahez-snow/AI-medichatbot/tree/main)] 

---

## 📌 Project Overview

NovaCure-AI is designed to simulate a professional medical consultation workflow by:

- Collecting patient symptoms interactively 💬  
- Extracting medically relevant symptoms using NLP 🔍  
- Predicting possible diseases using a trained ML model 🧬  
- Generating structured medical advisory reports 🤖  
- Delivering results through a modern Streamlit interface 🎨  

This project demonstrates real-world integration of **ML + Generative AI + Web Deployment** in the healthcare domain.

---

## 🧠 System Architecture

User Input 👤  
⬇  
Gemini NLP Symptom Extraction 🔍  
⬇  
Multinomial Naive Bayes Disease Prediction 🧬  
⬇  
Gemini AI Medical Advisory Generation 📜  
⬇  
Streamlit Chat-Based UI 🎨  

---

## 🚀 Key Features

### 🔹 Intelligent Symptom Extraction
- Converts natural language into standardized medical terms  
- Removes duplicates  
- Excludes negated symptoms (e.g., "no fever")  
- Ignores non-medical expressions  

### 🔹 Machine Learning Disease Prediction
- Model: Multinomial Naive Bayes  
- Lightweight and fast  
- Binary symptom vector input  
- Accuracy evaluated during training  

### 🔹 Structured Medical Advisory Report
Generated report includes:

1. 🩺 Condition Overview  
2. 💊 Medication Guidance (generic names only)  
3. 🏠 Home Care & Precautions  
4. 🥗 Diet & Hydration Advice  
5. 🚨 Emergency Warning Signs  
6. 🛡 Preventive Measures  
7. ⚠ AI Disclaimer  

### 🔹 Advanced User Interface
- Futuristic medical-themed design 🌌  
- Chat-based interaction 💬  
- Session profile dashboard 📊  
- Consultation reset option 🔄  

---

## 🛠 Technology Stack

- 🐍 Python  
- 📊 Scikit-Learn  
- 🤖 Google Gemini 2.5 Flash  
- 🌐 Streamlit  
- 📦 Pickle  
- 🔗 Requests  

---

## 📂 Project Structure

```
healthcare_chatbot_AI/
│
├── model_train.py
├── app.py
├── disease_model.pkl
├── symptom_list.pkl
├── requirements.txt
└── README.md
```

---

## 🧪 Model Training

The `model_train.py` script:

- Loads and cleans dataset  
- Splits data into training and testing sets  
- Trains Multinomial Naive Bayes model  
- Evaluates model accuracy  
- Saves:
  - `disease_model.pkl`
  - `symptom_list.pkl`

Run training locally:

```bash
python model_train.py
```

---

## 💻 Running the Application Locally

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Start Streamlit App

```bash
streamlit run app.py
```

---

## 🔐 API Configuration

Set your Google Gemini API key inside `app.py`:

```python
genai.configure(api_key="YOUR_API_KEY")
```

⚠ Important: Never expose your API key in public repositories. Use environment variables in production.

---

## 📊 Machine Learning Details

- Algorithm: Multinomial Naive Bayes  
- Input: Binary symptom vector  
- Output: Predicted disease label  
- Designed for lightweight deployment  

---

## ⚠ Disclaimer

This system is intended for educational and research purposes only.  

It does **not** replace professional medical diagnosis or treatment.  
Always consult a licensed healthcare provider for medical advice.

---

## 🔮 Future Enhancements

- 🏥 Hospital recommendation system  
- 📍 Nearby clinic integration  
- 📊 Prediction confidence visualization  
- 🧠 Deep learning model upgrade  
- 🌍 Multi-language support  
- 📱 Mobile optimization  

---

## 👩‍💻 Author
Mahesh K
Developed as an advanced AI healthcare application integrating Machine Learning and Generative AI technologies.

If you find this project useful, consider ⭐ starring the repository.
