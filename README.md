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

## How to Run Locally
1. Clone this repository
   git clone https://github.com/yourusername/medical-imaging-ai
2. Install dependencies
   pip install -r requirements.txt
3. Add your Google API key in app.py
4. Run the app
   streamlit run app.py

## ⚠️ Disclaimer
This tool is for educational purposes only and is not a substitute 
for professional medical diagnosis.
