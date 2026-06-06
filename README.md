# MediAssist AI

MediAssist AI is an intelligent medical report analysis platform that helps users understand complex healthcare reports through AI-powered explanations in simple language.

The system extracts important medical parameters from uploaded reports, identifies abnormal values, generates personalized health insights, and provides an interactive AI health assistant capable of answering questions in both English and Tamil.

---

## Overview

Medical reports often contain technical terminology and numerical values that are difficult for patients to interpret. MediAssist AI bridges this gap by transforming clinical data into clear, understandable information.

Users can upload laboratory reports, receive automated analysis, view simplified summaries, and interact with an AI assistant to gain a better understanding of their health metrics.

---

## Features

### Medical Report Upload

- Upload PDF medical reports
- Secure document processing
- Fast report analysis

### Intelligent Data Extraction

- Hemoglobin
- White Blood Cell Count (WBC)
- Red Blood Cell Count (RBC)
- Platelets
- Vitamin Levels
- Blood Sugar
- Cholesterol
- Additional laboratory parameters

### AI-Powered Health Insights

- Detect abnormal values
- Highlight health concerns
- Generate report summaries
- Explain medical terminology

### Multilingual Support

- English explanations
- Tamil explanations
- Language-aware AI responses

### AI Health Assistant

Users can ask questions such as:

```text
What is Hemoglobin?

Why is my Vitamin D level low?

Can low hemoglobin cause fatigue?

தமிழில் விளக்குங்கள்
```

The assistant provides contextual explanations based on the uploaded report.

---

## How It Works

```text
Medical Report
       │
       ▼
OCR Processing
       │
       ▼
Text Extraction
       │
       ▼
Medical Parameter Detection
       │
       ▼
Health Analysis Engine
       │
       ▼
AI Summary Generation
       │
       ▼
Interactive Health Assistant
```

---

## Technology Stack

### Frontend

- HTML
- Tailwind CSS
- JavaScript

### Backend

- Python
- Flask

### Artificial Intelligence

- LangChain
- Ollama
- Llama 3.2

### Natural Language Processing

- spaCy
- Transformers

### OCR

- EasyOCR
- Tesseract OCR

### Database

- MongoDB

---

## Project Structure

```text
MediAssist/
│
├── backend/
│   └── app.py
│
├── frontend/
│   ├── static/
│   └── templates/
│       ├── home.html
│       └── dashboard.html
│
├── uploads/
│
├── models/
│
└── README.md
```

---

## Future Enhancements

- Voice-based health assistant
- Health score prediction
- Medical report comparison
- Doctor recommendation system
- Multi-language support
- Mobile application
- Personalized health tracking

---

## Disclaimer

MediAssist AI is intended for educational and informational purposes only.

The platform does not provide medical diagnoses and should not replace professional medical advice, diagnosis, or treatment. Users should always consult qualified healthcare professionals regarding medical concerns.

---

## Vision

Our goal is to make healthcare information more accessible, understandable, and user-friendly through artificial intelligence.

MediAssist AI empowers patients by helping them better understand their medical reports and make informed healthcare decisions.
