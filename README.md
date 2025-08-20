# Multilingual GUVI Chatbot using GPT & Translation Models

This project implements a **multilingual chatbot** designed to enhance learning experiences on **GUVI**. The chatbot can interact in multiple languages by integrating **translation models** with a **fine-tuned GPT model**.

If a user inputs text in a non-English language:
1. The text is automatically translated to English.
2. The GPT model generates a response.
3. The response is translated back into the user's original language.

The system is deployed on **Hugging Face Spaces**, providing a clean, interactive **Streamlit UI** for real-time conversations.

---

## 🚀 Problem Statement
Many platforms limit chatbots to English, restricting accessibility for non-English speakers. This project bridges that gap using **translation + GPT-based response generation**, enabling **multilingual support** for users.

---

## 💼 Business Use Cases
1. **Customer Support Automation**
   - Handle queries in regional languages automatically.
   - Respond in the user's language without extra hiring.

2. **E-Learning Platforms**
   - Assist GUVI learners in their native language.
   - Provide course guidance, enrollment support, and technical help.

3. **Career Guidance & Mentorship**
   - Suggest learning paths (e.g., Data Science, Full Stack Development).
   - Offer resources and simulate basic career counseling.

4. **Course Discovery & Recommendation**
   - Interactively recommend GUVI courses based on user input.

---

## 🛠️ Approach
1. **Model Selection** – Fine-tuned GPT model for generating responses, supported by translation models for multiple languages.
2. **Translation Logic** – Detect user language and translate to/from English dynamically.
3. **UI/UX (Streamlit)** – Clean interface with input box, language selector, copy button, and clear text options.
4. **Error Handling** – Graceful handling of model failures, unsupported languages, and large inputs.
5. **Deployment** – Streamlit app hosted on Hugging Face Spaces.
6. **Version Control** – GitHub repository with proper commits, documentation, and versioning.

---

## 🔧 Notebook Overview

- **Data Preparation** – Tokenization and preprocessing for GPT fine-tuning.
- **Model Fine-Tuning** – Using Hugging Face Transformers library.
- **Translation Integration** – Automatic language detection and translation pipeline.
- **Streamlit Interface** – Real-time input/output handling with language selector.
- **Testing & Deployment** – Deploy on Hugging Face Spaces.

---

## ✅ Results
- Fully functional **multilingual chatbot** with real-time responses.
- Supports multiple languages for input/output.
- **Scalable deployment** using Hugging Face Spaces.
- Detailed **documentation** and version-controlled repository.


## 🌐 Live Demo  

> 🎉 The chatbot is live on **Hugging Face Spaces**!  
> Click below to interact with it in your favorite language:  

👉 [**Launch Multilingual GUVI Chatbot** 🚀](https://huggingface.co/spaces/AnnieVin/Multilingual_Guvi_Chatbot)
