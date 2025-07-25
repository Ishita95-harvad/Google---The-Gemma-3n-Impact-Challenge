# Google-Gemma-3n-hackathon

🧠 ****LegalMate Edge** – Real-Time AI Legal Companion on NVIDIA Jetson**

🚀**Overview**

LegalMate Edge is a cutting-edge GenAI-powered legal assistant designed to run entirely on-device using the NVIDIA Jetson platform and Gemma 3n LLM. It enables offline legal clause analysis, OCR-powered document scanning, and context-aware contract feedback—all on a lightweight edge device, making legal AI portable, secure, and cost-efficient.

#### 🔧 Key Features
✅ **Multimodal Interface**: Upload PDF/Images with contracts → Live clause detection via OCR + NLP.

✅**On-Device Clause Extraction**: Leverages Gemma 3n + Jetson to parse NDAs, SLAs, rental agreements, etc.

✅ **Privacy-First Legal AI**: Runs fully offline on Jetson, ensuring data never leaves the device.

✅ **Voice & Visual Interaction**: Input via microphone or camera, output via speech and highlights.

✅ **Realtime Feedback**: Suggests risk flags, missing clauses, and potential negotiation points.

#### 🔌 Technologies Used

-Stack	Tools/Frameworks
-LLM	Gemma 3n (3B, via Ollama on-device)
-OCR	Tesseract + EasyOCR
-Deployment	NVIDIA Jetson Nano / Xavier NX
-Interface	React + Streamlit + Firebase
-Finetuning	Unsloth + QLoRA (low-rank adapter)
-Backend	FastAPI + TorchServe

#### 🔍 Example Use Case

A lawyer scans a printed contract using the Jetson-powered LegalMate device at a remote site with no internet. In real time, the device extracts legal clauses, flags missing indemnity terms, and suggests rephrasing—all securely, without any data ever leaving the device.
