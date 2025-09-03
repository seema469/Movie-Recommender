
# 🎬 Movie Recommender Agent

An **AI-powered movie recommendation system** that integrates **multi-modal AI agents**, live web search, and image analysis to recommend G/PG-rated movies.  
This project demonstrates **Agentic AI**, **AutoGen orchestration**, and **tool integrations** to create an intelligent conversational movie assistant.

---

## 🚀 Features

| Capability                     | Description                                                                                      |
|-------------------------------|--------------------------------------------------------------------------------------------------|
| 🖼️ **Poster Analysis**         | Analyzes movie posters using GPT-4o-mini to describe style, tone, and genre hints.             |
| 🔍 **Smart Recommendations**   | Finds and recommends similar movies (G/PG-rated) via search tools like **Google Serper**.      |
| 🤖 **Agent-Oriented Design**   | Uses **Microsoft AutoGen AgentChat** with `AssistantAgent` and `RoundRobinGroupChat` for reasoning. |
| 🌐 **Live Web Search**         | Integrates **LangChain** and **MCP server tools** to fetch real-time movie data.               |
| 🗂️ **Structured Outputs**      | Summarizes results in a clean, user-friendly format.                                           |
| 🔑 **Secure Setup**            | API keys managed through `.env` for TMDB, OpenAI, and Serper APIs.                             |
| 📦 **Modular Notebook**        | Interactive Jupyter Notebook for experimentation and demos.                                    |

---

## 🧩 Project Architecture


1. **Input:** User enters a movie title/year.  
2. **Poster Analysis:** Agent describes poster elements and style.  
3. **Search & Retrieval:** Tools fetch data on similar movies (filtered by G/PG rating).  
4. **Recommendation Logic:** AutoGen agents reason over data to choose top matches.  
5. **Results:** Display posters, summaries, and metadata.  

---

## 🛠️ Tech Stack

| Layer                        | Tools & Libraries                                                   |
|-----------------------------|---------------------------------------------------------------------|
| **Agent Framework**         | Microsoft AutoGen, AutoGen AgentChat                               |
| **LLM Models**              | OpenAI GPT-4o-mini                                                 |
| **Data Sources**            | TMDB API, Google Serper                                            |
| **Orchestration**           | LangChain, MCP Server Tools                                        |
| **Visualization**           | Pillow (PIL), IPython Display                                      |
| **Environment Management**  | Python 3, Jupyter Notebook, dotenv                                 |

---

## 🧾 Skills Highlight

- **Agentic AI:** Designing and orchestrating AI agents to collaborate and reason dynamically.  
- **Multi-Modal AI:** Integrating image and text inputs for intelligent movie analysis.  
- **LangChain Tooling:** Building agent tools for internet search and content retrieval.   
- **AutoGen Workflows:** Structuring multi-agent interactions with `RoundRobinGroupChat`.  
- **API Integrations:** Securely consuming TMDB, Serper, and OpenAI APIs.  
- **System Design:** Creating scalable recommendation pipelines using modular design.  

---

## 📂 Project Structure

```
.
├── my_movie_recommender_agent.ipynb   # Main notebook with agents and workflows
├── requirements.txt                   # Python dependencies
├── README.md                          # Project documentation
├── sandbox                            # Write recommended results in file
└── .env                               # API keys (ignored in Git)
```

---

## ⚙️ Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/movie-recommender-agent.git
    cd movie-recommender-agent
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up API Keys**:
    Create a `.env` file with your credentials:
    ```bash
    TMDB_API=your_tmdb_api_key
    OPENAI_API_KEY=your_openai_api_key
    SERPER_API_KEY=your_serper_api_key
    ```

4. **Run the Notebook**:
    ```bash
    jupyter notebook my_movie_recommender_agent.ipynb
    ```

---

## 📌 Future Roadmap

- 📊 Add personalized recommendations using user profiles.  
- 🎥 Include trailers and streaming availability.  
- 🔍 Add vector-based image similarity for poster matching.  
- 🌐 Deploy as a **web app** or **Slack bot** for real-time movie discovery.  

---

## 📜 License
This project is licensed under the **MIT License**.  
Contributions are welcome!
