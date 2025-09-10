# Create README.md with EduTutor project details

readme_content = """
# EduTutor AI 🎓🤖

EduTutor AI is a personalized learning assistant built with **IBM Granite AI models**.  
It provides two main features:
1. 📘 **Concept Explanation** – Enter any concept and get a detailed explanation with examples.  
2. 📝 **Quiz Generator** – Generate 5 quiz questions with answers for any topic.  

This project runs on **Google Colab** using Hugging Face IBM Granite models and **Gradio** for the user interface.  

---

## 🚀 Features
- AI-powered concept explanations  
- Automatic quiz generator (MCQ, True/False, Short Answer)  
- Runs on Google Colab with GPU support  
- Public Gradio link for easy sharing  

---

## 🛠️ Tech Stack
- Python  
- Hugging Face (IBM Granite Models)  
- Transformers & Torch  
- Gradio  
- Google Colab  

---

## ▶️ How to Run

### On Google Colab
Open directly in Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1W4fxaEARQ4hkzc69H8WO9Z506oOWt003)

Steps:
```bash
!pip install transformers torch gradio -q
!python edututor_ai.py
