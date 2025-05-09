# 🤖 CTSE ML Chatbot

This is an intelligent chatbot for answering questions related to the CTSE course. It uses LangChain, Google Gemini, and HuggingFace embeddings to process and query PDF/PPTX lecture materials.

---

## 📁 Project Structure

<ul>
  <li>CTSE_ML_CHATBOT\</li>
  <li>Chroma_db # Stores vector database</li>
  <li>data_sets # Place your PDF/PPTX lecture notes here</li>
  <li>.env # Environment file for storing API key</li>
  <li>requirements.txt # Python dependencies</li>
  <li>chatbot.ipynb # Jupyter notebook version</li>
</ul>


---

## 🛠️ Setup Instructions

### 1. 📦 Install Python Dependencies

Make sure Python 3.9+ is installed. Then install all required packages:

pip install -r requirements.txt

### 2. 🔐 Set Your Google API Key

GOOGLE_API_KEY=your_actual_google_api_key_here

### 3. 🚀 Run the Chatbot

