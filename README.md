# LangChain Text Summarizer 🦜

A professional Streamlit application that uses Generative AI to summarize content from YouTube videos or any website URL. 

## 🚀 Features
- **YouTube Summarization:** Automatically fetches transcripts and provides a concise summary.
- **Web Scraping:** Extracts text from any provided URL using `UnstructuredURLLoader`.
- **Fast Inference:** Powered by Groq's LPU™ Inference Engine for near-instant responses.
- **Modern Stack:** Built with LangChain Expression Language (LCEL) for robust AI orchestration.

## 🛠️ Tech Stack
- **Framework:** Streamlit
- **AI Orchestration:** LangChain
- **LLM:** Llama-3.1-8b-instant (via Groq)
- **Environment:** Python 3.10+

## ⚙️ Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone  https://github.com/bibhudas005-cmyk/text-summarizer.git
   
  
  
2.INSTALL DEPENDENCIES
pip install -r requirements.txt

3.Configure Environment Variables:
Create a .env file in the root directory and add your API key:
GROQ_API_KEY="your_gsk_key_here"

4.Run the Application:
streamlit run app.py