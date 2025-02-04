# MUET-GPT

## Overview
MUET Chatbot is an AI-powered virtual assistant designed to help students easily access information about Mehran University of Engineering and Technology (MUET). It eliminates the hassle of navigating the official website by providing instant, accurate, and up-to-date responses to university-related queries.

## Features
- **Real-time Information Retrieval:** Uses Tavily Search to fetch the latest details from reliable sources.
- **Retrieval-Augmented Generation (RAG):** Enhances response accuracy by retrieving relevant data from the MUET prospectus.
- **Conversational AI:** Provides human-like responses using OpenAI's GPT-3.5.
- **Streamlit UI:** Simple and interactive interface with the official MUET logo.
- **Efficient Search:** FAISS-based vector store ensures quick retrieval of relevant university details.

## Technologies Used
- **Streamlit** (Frontend UI)
- **LangChain** (Agents, RAG, and Prompt Engineering)
- **FAISS** (Vector Store for document retrieval)
- **OpenAI GPT-3.5** (Language model for response generation)
- **Tavily Search API** (For real-time web search)
- **PyPDFLoader** (Processing university documents)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/muet-chatbot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd muet-chatbot
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Set up environment variables:
   - Create a `.env` file and add your OpenAI API key:
     ```
     OPENAI_API_KEY=your_openai_api_key
     ```
6. Run the chatbot:
   ```bash
   streamlit run app.py
   ```

## Usage
- Enter your query in the chat interface.
- The chatbot retrieves information from the MUET prospectus and real-time sources.
- Get instant, accurate answers without browsing the website.

## Future Enhancements
- **Multilingual support** for wider accessibility.
- **Voice-based interaction** for hands-free operation.
- **Expanded knowledge base** with faculty directories and course details.

## Contributors
Developed by Haseebullah and team for university students at MUET.

## License
This project is licensed under the MIT License.

---
Feel free to contribute and improve the chatbot! 🚀


