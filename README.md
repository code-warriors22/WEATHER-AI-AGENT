# 🚀 LangChain AI Agent

A lightweight, modular AI Agent built with **LangChain** for learning, experimentation, and rapid prototyping. This project demonstrates how to integrate Large Language Models (LLMs), external APIs, and environment-based configuration into a simple Python application.

Whether you're getting started with LangChain or building your own AI-powered assistant, this repository provides a clean and extensible foundation.



#  Features

* 🤖 LangChain-based AI Agent
* 🔑 Secure API key management using `.env`
* 🌐 External API integration (OpenAI, Tavily, WeatherStack)
* 🧩 Modular Python project structure
* 📓 Jupyter Notebook for experimentation and research
* ⚡ Lightweight and beginner-friendly implementation
* 🛠 Easy to extend with custom tools and agents



#  Tech Stack

| Technology        | Purpose                         |
| ----------------- | ------------------------------- |
| Python 3.10.11    | Programming Language            |
| LangChain         | AI Agent Framework              |
| gemini API        | Large Language Model            |
| Tavily Search API | Web Search Tool                 |
| WeatherStack API  | Weather Information             |
| python-dotenv     | Environment Variable Management |
| Requests          | HTTP API Calls                  |
| Jupyter Notebook  | Research & Experimentation      |

# 📂 Project Structure

text
.
├── .env
├── README.md
├── app.py                 # Main application entrypoint
├── main.py                # Alternative execution script
├── requirements.txt
└── research/
    └── agent_demo.ipynb   # Experiments and research notebook




#  Architecture


                User
                  │
                  ▼
          Python Application
          (app.py / main.py)
                  │
                  ▼
          Environment Loader
             (.env file)
                  │
                  ▼
         LangChain AI Agent
                  │
      ┌───────────┼───────────┐
      │           │           │
      ▼           ▼           ▼
 OpenAI API   Tavily API   WeatherStack API
      │           │           │
      └───────────┼───────────┘
                  ▼
            Final AI Response




# ⚙️ Prerequisites

* Python **3.10.11**
* Conda (recommended) or any Python virtual environment
* API Keys:

  * GOOGLE GEMINI
  * Tavily
  * WeatherStack



#  Installation

# 1. Clone the Repository

bash
git clone https://github.com/your-username/langchain-agent.git

cd langchain-agent


## 2. Create a Virtual Environment

### Using Conda

bash
conda create -n langagent python=3.10.11 -y

conda activate langagent


### Or using venv

bash
python -m venv venv


Activate the environment:

Windows

bash
venv\Scripts\activate


Linux / macOS

bash
source venv/bin/activate




## 3. Install Dependencies

bash
pip install -r requirements.txt




#  Environment Variables

Create a `.env` file in the project root.

env
GEMINI_API_KEY = your_gemini_api_key

TAVILY_API_KEY=your_tavily_api_key

WEATHERSTACK_API_KEY=your_weatherstack_api_key


> Security Notice:** Never commit your `.env` file or API keys to GitHub. Keep all secrets private.



#  Running the Project

Run either of the available entry points.

bash
python app.py


or

bash
python main.py
or 
streamlit run app.py
or 
streamlit main.py




#  Research Notebook

To explore experiments and prototype workflows, launch the Jupyter Notebook:

bash
jupyter notebook research/agent_demo.ipynb



#  Dependencies

Some of the major packages used in this project include:

* LangChain
* LangChain Community
* LangChain Core
* langchain_google_genai
* python-dotenv
* requests
* Tavily Python
* Streamlit (optional UI support)



#  Future Improvements

*
* Multi-agent workflows
* Streamlit web interface
* Support for multiple LLM providers
* Voice input/output
* Docker support
* CI/CD pipeline integration
* RAG with Vector Database
* Deployment on Render or AWS



#  Contributing

Contributions are always welcome.

If you'd like to improve this project:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

Bug reports, feature requests, and documentation improvements are greatly appreciated.

#



#  Author

**Abhishek Saket**

AI & Machine Learning Enthusiast

Feel free to connect, contribute, or share feedback.
