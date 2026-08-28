1. LLM Pratikleri

   1. Projenin Oluşturulması ve Sanal Ortam
       python -m venv venv
       .\venv\scripts\activate
   
   2. Kütüphane Kurulması
       langchain
       langchain-google-genai
       python-dotenv
       pip install -r requirements.txt
   
   3. Gemini api key
       .env: GOOGLE_API_KEY=" "

   4. İlk Gemini Çağrısı Yapılması


2. RAG

   1. Proje yapısı
       mil_std_document.py
       create_vector_db.py
       rag.py

   2. Kütüphane kur
       langchain
       langchain-google-genai
       langchain-community
       langchain-text-splitters
       faiss-cpu
       python-dotenv
       pip install -r requirements.txt

    3. mil-std doküman oluşturma
        https://github.com/turkiyeyapayzekaakademisi/llm-rag-memory-ai-agents


3. Agent