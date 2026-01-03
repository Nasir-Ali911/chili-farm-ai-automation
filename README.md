# Chili Farm AI Export Automation 🌶️🤖

This project is a RAG-based automation agent built to help Pakistani chili farmers automate export document processing.

### 📺 [Watch the Video Demo Here](https://www.facebook.com/groups/learnaiml/posts/834523416255383/)

## 🚀 Overview
Using a Retrieval-Augmented Generation (RAG) architecture, this system extracts data from unstructured PDF inquiries and notifies farmers via WhatsApp.

**Key Features:**
- **AI Extraction:** Uses Google Gemini to parse complex PDF data.
- **Data Storage:** Syncs structured data to Supabase.
- **Real-time Alerts:** Sends instant notifications via WhatsApp.
- **Mentorship:** Developed under the guidance of **Sir Zafar Iqbal** in the AI/ML Training program.

## 🛠️ Technical Stack
- **n8n** (Orchestration)
- **Google Gemini** (LLM / RAG)
- **Supabase** (Database)
- **WhatsApp API** (Interface)

## 📂 How to Use
I have included the `chili exports guide agent.json` file in this repository. 
1. Install [n8n](https://n8n.io/).
2. Import the `.json` file into your n8n workflow editor.
3. Configure your Gemini and Supabase credentials.
