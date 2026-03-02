# 🚀 Smart Resume Filter

An intelligent hiring automation system that streamlines resume screening using AI, vector search, and workflow automation.


## 📌 Project Overview

The AI-Powered HR Automation System automates the candidate screening process by analyzing resumes against job descriptions using Artificial Intelligence.

When a candidate submits their resume and selects a job role, the system:

- Automatically downloads the resume
- Retrieves the relevant job description
- Converts documents into embeddings
- Stores and searches data using a vector database
- Uses AI to evaluate resume-job compatibility
- Generates suitability analysis
- Returns structured evaluation results

This eliminates manual resume screening and improves hiring efficiency.


## ✨ Key Features

- 📄 Resume Upload via Form
- 🎯 Job Role Selection (Backend, Frontend, SQA, Data Scientist)
- 📂 Automatic Job Description Retrieval (Google Drive)
- 🤖 AI Resume Analysis using Google Gemini
- 🧠 Vector Search with Pinecone
- 💬 AI Agent with Memory
- 📡 Webhook-based API Endpoint
- 🔍 Smart Resume-Job Matching
- 📊 Structured Evaluation Output


## 🛠 Tech Stack

- **Automation Platform:** n8n
- **AI Model:** Google Gemini
- **Embeddings:** Gemini Embeddings
- **Vector Database:** Pinecone
- **File Storage:** Google Drive
- **Agent Framework:** LangChain (via n8n)
- **API Handling:** Webhooks (REST)


## 🔄 System Workflow

### 1️⃣ Form Submission
Candidate submits:
- Selected Job Role
- Resume (PDF)

### 2️⃣ File Processing
- Resume file is split and extracted
- Switch logic identifies job role
- Corresponding job description is fetched from Google Drive

### 3️⃣ Data Embedding
- Resume content converted into embeddings
- Stored inside Pinecone vector database

### 4️⃣ AI Evaluation
- AI Agent retrieves relevant job data
- Compares resume with job requirements
- Generates structured evaluation

### 5️⃣ Response Handling
- Results returned via webhook
- Ready for logging or notification system

## 📡 API Endpoint

### POST Request


