# TEJAS – AI-Powered Employee Assistance Chatbot for GAIL
 
## 📽️ Demo Preview

> Click the image below to watch the full demo on YouTube.

[![Screenshot 2025-06-18 at 4 00 10 PM](https://github.com/user-attachments/assets/e26e31d5-f464-41c3-a059-b63632ac830e)](https://www.youtube.com/watch?v=PxhodRU9kQ8)

[![Watch Demo](https://img.shields.io/badge/Watch-Demo-red?logo=youtube)](https://www.youtube.com/watch?v=PxhodRU9kQ8)

TEJAS is an intelligent, real-time, multilingual chatbot built to revolutionize employee support at **GAIL (India’s largest state-owned natural gas producer and distributor)**. It enables fast, efficient query resolution for HR, IT, and administrative issues, replacing inefficient paper-based systems.

---

## 🚀 Key Features

- 🤖 **AI-Powered Assistance**: Uses LLMs (GROQ, HuggingFace, Llama) and NLP to handle complex employee queries in real-time.
- 📄 **Document Upload & Summarization**: Extracts and summarizes text from uploaded documents using OCR.
- 🔊 **Voice-to-Text Support**: Accepts voice queries and converts them to text for processing.
- 🔐 **Secure Access**: Integrates 2-Factor Authentication (2FA) via email.
- 🌐 **Multilingual Support**: Offers assistance in multiple languages.
- 📚 **Contextual Memory**: Stores previous chats for historical reference and continuity.
- ⚙️ **Scalable Architecture**: Handles 30+ concurrent users with <5s response time.
- ☁️ **Deployed on AWS, Vercel, Docker, Kubernetes**: Ensures high availability and fault tolerance.
- 💾 **Tech Stack**: Python, MongoDB, Redis, Streamlit, LangChain, FastAPI

---

## 🧠 Project Architecture

- **Frontend**: Streamlit (UI for chat + document interaction)
- **Backend**: FastAPI for endpoint exposure, Redis for caching
- **LLMs**: HuggingFace Transformers, Llama, GROQ
- **Storage**: MongoDB for chat history and document metadata
- **Deployment**: AWS (Compute), Vercel (UI), Docker + Kubernetes (Containerization)
- **Authentication**: Custom 2FA with email

---

## 📽️ Demo

👉 [Watch Full Demo](https://www.youtube.com/watch?v=PxhodRU9kQ8)

---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gail_chatbot_tejas.git
cd gail_chatbot_tejas
```

### 2. Set up a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add API keys to `.env`

Create a `.env` file in the root directory and add the following:

```env
LANGCHAIN_API_KEY=your_key_here
HUGGINGFACE_API_KEY=your_key_here
GROQ_API_KEY=your_key_here
MONGODB_URI=your_connection_string
EMAIL_AUTH_SECRET=your_2FA_secret
```

### 5. Run the project

```bash
streamlit run pdfapp.py
```

---

## ⚠️ Known Challenges

- **Data Privacy**: Mitigated through strong encryption & compliance.
- **Scalability**: Load-tested to handle >30 users; future-ready with cloud scaling.
- **User Adoption**: Addressed with guided onboarding and user training modules.

---

## 📈 Impact at GAIL

- ⏱️ Reduced response time from hours to seconds
- 📉 Decreased paperwork and boosted sustainability
- 🔊 Improved inclusivity via voice & multilingual support
- 🔄 Enhanced onboarding and internal communication

---

## 🤝 Contributions

We welcome contributions! Please open issues or submit pull requests for improvements or bug fixes.

---

## 📄 License

MIT License

---

## 📌 Tags

`#LLM` `#NLP` `#Chatbot` `#OCR` `#Multilingual` `#AI` `#MLOps` `#FastAPI` `#Streamlit` `#GAIL` `#TEJAS`
