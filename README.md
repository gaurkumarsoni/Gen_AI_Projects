# 🌍 GenAI Language Translator

A sleek, high-performance translation application built with **Streamlit**, **LangChain**, and **OpenAI's GPT-4o-mini**. This tool allows users to translate text between multiple languages seamlessly while maintaining context and nuance.

## 🚀 Features
* **LLM Powered:** Uses `gpt-4o-mini` for fast and cost-effective translations.
* **Context Aware:** Leverages LangChain prompts to ensure translations are accurate, not just literal.
* **User-Friendly UI:** Built with Streamlit for a clean, responsive web interface.
* **Multi-language Support:** Easily adaptable to any language pair supported by OpenAI.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** [Streamlit](https://streamlit.io/)
* **Orchestration:** [LangChain](https://www.langchain.com/)
* **Model:** OpenAI `gpt-4o-mini`

---

## 📋 Prerequisites
Before you begin, ensure you have the following:
* Python 3.9 or higher installed.
* An OpenAI API Key.

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/gaurkumarsoni/Gen_AI_Projects.git](https://github.com/gaurkumarsoni/Gen_AI_Projects.git)
   cd Gen_AI_Projects/src

2. **Create and activate a virtual environment:**
   ```bash
    python -m venv .venv
    # On Windows:
    .venv\Scripts\activate
    # On Mac/Linux:
    source .venv/bin/activate

2. **Install dependencies:**
   ```bash
    pip install -r requirements.txt
   
3. **Set up environment variables:** Create a .env file in the src directory and add your OpenAI key:
     ```bash
      OPENAI_API_KEY=your_api_key_here
     
## 🏃 Running the App
Start the Streamlit server by running:

    ```bash
    streamlit run main.py
    
## 📂 Project Structure
    ```bash
    src/
    ├── main.py          # Streamlit UI and app logic
    ├── utils/           # Helper functions & LangChain chains
    ├── config/          # Configuration settings
    └── requirements.txt # Project dependencies
    
## 🤝 Contributing
Feel free to fork this repo and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
