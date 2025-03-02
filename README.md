# 🏥 CDSS - Clinical Decision Support System

An advanced AI-powered platform for analyzing medical data, assisting in disease diagnosis, and providing intelligent healthcare insights. This platform integrates various diagnostic tools and an AI Medical Bot to enhance patient care and clinical decision-making.

---

## 📌 Features  

### 🔍 Disease Diagnosis  
- Analyze patient symptoms and predict potential health conditions accurately.  
- Provides a fast and reliable diagnosis using advanced AI models.  

### 📊 Diagnosis CDSS (Clinical Decision Support System)  
- Supports healthcare professionals by analyzing patient data and medical records.  
- Facilitates informed decision-making with intelligent insights.  

### 🧪 Blood Report Analyzer  
- Upload blood reports in PDF format for detailed analysis.  
- Extracts key parameters (e.g., glucose, hemoglobin) and provides actionable insights.  

### 🔬 Research Insights  
- Access in-depth medical research and valuable insights.  
- Enhances patient care by providing evidence-based information.  

### 🩻 X-Ray Analysis  
- Detect pneumonia through advanced X-ray image analysis.  
- Offers accurate and quick evaluation for early diagnosis.  

### 🤖 AI Medical Bot  
- An intelligent chatbot for real-time medical assistance.
- Supports multilingual input for both voice and text communication.
- Responds to doctors queries, guides through diagnostics, and provides medical advice.  

---

## Project Structure

```bash
CDSS/
├── frontend/                 # React
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── static/
│   │   │   ├── css/
│   │   │   └── images/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── backend/                  # Flask
│   ├── data/
│   ├── models/
│   ├── faiss_cdss_store/
│   ├── faiss_sysmptoms_store/
│   ├── script/
│   ├── app.py
│   └── .env
│
└── X-Ray-System-server/      # Flask
    ├── models/
    ├── keras/
    ├── static/
    ├── templates/
    └── app.py
```

## 🏗 Technologies & Frameworks
- *Generative AI (Gemini)* – Provides intelligent medical insights.  
- *RAG (Retrieval-Augmented Generation)* – Enhances response accuracy.  
- *Vector Databases* – Fast & efficient search for medical knowledge.  
- *Google Translate API* – Enables multilingual communication.  
- *Speech Recognition (STT & TTS)* – Enables voice-based interactions.  
- *Flask* – Backend API development.  
- *React* – Interactive frontend UI.  

## 💡 How It Solves the Problem
- *Real-time Medical Insights* – Fetches & summarizes latest research.
- *Patient-Specific Recommendations* – Integrates EHR data with AI.
- *AI-Assisted Diagnostics* – Predicts diseases based on symptoms & reports.
- *Multilingual Accessibility* – Supports diverse patient demographics.

## ⚡ Innovation & Uniqueness
- *Combines RAG & CDSS* for *context-aware medical insights*.
- *AI-driven decision support* for *doctors & healthcare professionals*.
- *Seamless integration of structured (EHR) & unstructured (research papers) data*.
- *Multilingual, voice-enabled chatbot for accessibility*.

