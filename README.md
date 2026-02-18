# 🩺 Medical Image Analysis AI Agent

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-red)
![Gemini](https://img.shields.io/badge/Google-Gemini2.0-green)

## Overview
An AI-powered medical imaging analysis tool that accepts X-rays, MRIs, 
CT scans, and ultrasounds and returns detailed diagnostic reports using 
Google Gemini 2.0 and real-time medical research via DuckDuckGo search.

## Features
- Upload any medical image (X-ray, MRI, CT, Ultrasound)
- AI analysis powered by Google Gemini 2.0 Flash
- Real-time research using DuckDuckGo medical literature search
- Structured diagnostic report with patient-friendly explanation
- Built with Streamlit for instant web interface

## Tech Stack
| Tool | Purpose |
|------|---------|
| Google Gemini 2.0 | Medical image analysis |
| Agno Framework | AI agent orchestration |
| DuckDuckGo Search | Medical literature retrieval |
| Streamlit | Web interface |
| Pillow | Image preprocessing |


## How to Reproduce This Project

### Prerequisites
- Python 3.10 or higher
- A Google Gemini API key from https://aistudio.google.com

### Step by Step

1. **Clone the repository**
```
   git clone https://github.com/Tsion-Woldeselassie/medical-imaging-ai
   cd medical-imaging-ai
```

2. **Create a virtual environment**
```
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # Mac
```

3. **Install all dependencies**
```
   pip install -r requirements.txt
```

4. **Add your API key**
   - Open `app.py`
   - Replace the GOOGLE_API_KEY value with your own key from aistudio.google.com

5. **Run the app**
```
   streamlit run app.py
```

6. **Open your browser**
   - Go to http://localhost:8501
   - Upload a medical image using the sidebar
   - Click Analyze Image
5. Run the app
   streamlit run app.py

## ⚠️ Disclaimer
This tool is for educational purposes only and is not a substitute 
for professional medical diagnosis.
