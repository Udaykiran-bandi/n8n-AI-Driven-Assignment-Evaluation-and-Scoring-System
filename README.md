# n8n-AI-Driven-Assignment-Evaluation-and-Scoring-System

This repo contains an automated workflow built with **n8n**, designed to evaluate student assignments pdf's submitted in ZIP format. The system extracts question–answer pairs, sends them to an AI model for scoring, and replies to the user with a detailed evaluation.

---
<img width="1470" height="956" alt="AI-Driven Assignment Evaluation Snapshot" src="https://github.com/user-attachments/assets/53c96205-c504-4e9b-85a9-8ec7fca67b93" />

---

## 🔥 Features

* Accepts **ZIP files** containing multiple assignments
* Extracts PDFs automatically
* Reads and processes each Q&A pair
* AI-powered scoring using **Gemini Chat Model**
* Sends evaluation results directly via **Telegram**
* Loop-based processing for unlimited PDFs
* Simple, modular, and easy to customize

---

## 🧩 Workflow Steps

1. **Telegram Trigger** → User uploads ZIP assignment
2. **Decompress ZIP**
3. **Split PDFs**
4. **Loop Over Items**
5. **Extract Text from PDF**
6. **AI Agent** → Scoring & feedback
7. **Send Telegram message** with evaluation
8. **Wait** (optional pacing)

---

## 🛠️ Tools Used

* n8n
* Telegram Bot API
* Google Gemini Chat Model
* PDF Extraction
* ZIP Decompression

---

## ▶️ Setup

1. Import the `.json` workflow into n8n
2. Add your Telegram bot token
3. Add Gemini/OpenAI API key
4. Upload ZIP → receive graded assignment
