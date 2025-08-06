![Apache 2.0 License](https://img.shields.io/github/license/legalmate/legalmate-edge) 
![Jetson Powered](https://img.shields.io/badge/Jetson-Nano%20%7C%20Xavier%20NX-blue)
![Gemma Model](https://img.shields.io/badge/Gemma-3n%204B-multimodal) 
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Jetson Powered](https://img.shields.io/badge/Jetson-Nano%20%7C%20Xavier%20NX-blue) 
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Gemma Model](https://img.shields.io/badge/Gemma-3n--4B-multimodal-purple)


## LegalMate Edge – Jetson Edition 🧠  Real-Time AI Legal Companion on NVIDIA Jetson

**LegalMate Edge** is a lightweight legal document analysis tool optimized for **NVIDIA Jetson** devices using **Gemma 3n**, enabling multimodal understanding of legal contracts, even offline.


 ---------------------------------------
 
**AI-Powered Legal Contract Analyzer**- Automate contract **reviews**, **surface hidden risks, and ensure compliance — with speed, privacy, and security**.

🚀 **Overview**

LegalMate Edge is a cutting-edge GenAI-powered legal assistant designed to run entirely on-device using the NVIDIA Jetson platform and Gemma 3n LLM. It enables offline legal clause analysis, OCR-powered document scanning, and context-aware contract feedback—all on a lightweight edge device, making legal AI portable, secure, and cost-efficient.

------------------

**📁 Folder Structure:**
````
AI_Demo_Video_Kit/
├── assets/
│   └── screenshots/      ← Placeholder for visuals
├── contracts/
│   ├── NDA_Template.pdf  ← General Mutual NDA
│   └── SLA_Template.pdf  ← Standard SLA for services
├── scripts/
│   ├── voiceover_script.txt
│   └── storyboard_notes.md
├── video/
│   ├── storyboard.pdf    ← Printable storyboard
│   └── final_edit/       ← Placeholder for final video
├── README.md
└── LICENSE
`````
---------------------------

**🔍 Core Capabilities**

- **OCR + Clause Extraction**
Extract clauses from scanned PDFs and images using advanced OCR and layout-aware NLP.

- **Gemma-Driven Clause Evaluation**
Real-time detection of risks, NDA violations, termination clauses, and more using Gemma 3n on-device.

- **Edge Deployment**
Works fully offline on Jetson Nano / Xavier NX — ideal for field lawyers, remote legal teams, and enterprise-grade compliance.

- **Designed For**
🏛️ Law Firms | 📄 Contract Reviewers | 🛡 Compliance Teams

---

**🛠 Installation**

```bash

git clone https://github.com/legalmate/legalmate-edge.git
cd legalmate-edge
bash install.sh  # For Jetson setup

**# Google-Gemma-3n-hackathon**

`````````
 
------------------------------------------------------------------------------------

#### 🔧 Key Features

-  📦 **OCR + Clause Extraction** from scanned legal documents (NDAs, SLAs, rental agreements)

- 📦 **Gemma 3n + Jetson NLP**: Detects risk clauses, termination triggers, missing terms

- 🧠 **Gemini/Gemma Evaluation**: Context-aware legal reasoning with open weights
  
- 🔍 **Runs Fully Offline** on Jetson Nano / Xavier NX — privacy-first legal AI
 
- 🤖 **Multimodal Interface**: Upload PDF/Images with contracts → Live clause detection via OCR + NLP.

- 📄 **On-Device Clause Extraction**: Leverages Gemma 3n + Jetson to parse NDAs, SLAs, rental agreements, etc.

- 🔐  **Privacy-First Legal AI**: Runs fully offline on Jetson, ensuring data never leaves the device.

- 🎙️ **Voice & Visual Interaction**: Input via microphone or camera, output via speech and highlights.

- ⚠️ **Realtime Feedback**: Suggests risk flags, missing clauses, and potential negotiation points.

----------------

#### 🔌 Technologies Used

- **Stack**:	Tools/Frameworks
- **LLM**:	Gemma 3n (3B, via Ollama on-device)
- **OCR**:	Tesseract + EasyOCR
- **Deployment**:	NVIDIA Jetson Nano / Xavier NX
- **Interface**:	React + Streamlit + Firebase
- **Finetuning**:	Unsloth + QLoRA (low-rank adapter)
- **Backend** :	FastAPI + TorchServe

----------------

#### 🔍 Example Use Case

A lawyer scans a printed contract using the Jetson-powered LegalMate device at a remote site with no internet. In real time, the device extracts legal clauses, flags missing indemnity terms, and suggests rephrasing—all securely, without any data ever leaving the device.
