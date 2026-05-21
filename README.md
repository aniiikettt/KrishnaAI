# 🎙️ VoxMind AI – Real-Time Voice AI Assistant

VoxMind AI is a real-time voice AI assistant designed for low-latency, scalable voice interactions. Built with modern asynchronous backend architecture, it enables seamless voice communication, intelligent AI responses, and resilient execution with fallback handling.

## 🚀 Features

- ⚡ **Real-Time Voice Processing**
  - Supports low-latency bidirectional voice interactions
  - Built using WebSockets for instant communication

- 🧠 **AI-Powered Conversational Intelligence**
  - Integrates LLM-powered response generation
  - Supports voice-to-intelligence pipelines

- 🔄 **Hybrid Async Architecture**
  - Built with FastAPI + asyncio for scalable concurrent request handling
  - Prevents event-loop blocking for smooth execution

- 📊 **Latency Monitoring**
  - Tracks:
    - Total response latency
    - LLM inference time
    - Processing overhead
  - Helps optimize real-time performance

- 🛡️ **Fault Tolerance & Reliability**
  - Automated logging
  - Fallback handling for failures
  - Resilient execution flow

- 🗄️ **Database Support**
  - SQLite integration for lightweight persistence

---

## 🛠️ Tech Stack

| Technology | Purpose |
|----------|---------|
| Python | Core backend development |
| FastAPI | API framework |
| WebSockets | Real-time communication |
| asyncio | Async request handling |
| SQLite | Data persistence |
| Sarvam AI | Voice/AI integration |
| Logging | Monitoring & debugging |

---

## 🏗️ Architecture Overview

```text
User Voice Input
      ↓
Speech Processing Layer
      ↓
WebSocket Communication
      ↓
FastAPI Async Backend
      ↓
LLM Inference (Sarvam AI)
      ↓
Response Generation
      ↓
Latency Monitoring + Logging
      ↓
Voice Response Output
