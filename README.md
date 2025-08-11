# 📰 Agentic AI Project 3: End-to-End AI News Summarizer

![Python](https://img.shields.io/badge/Python-3.13%2B-brightgreen)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-News%20Summarizer-blue)
![Summarization](https://img.shields.io/badge/AI-Summarization-orange)
![License](https://img.shields.io/badge/License-GPL--3.0-orange)

A modern, agentic, end-to-end AI-powered news summarizer platform. This project uses modular agent design and graph-based orchestration to deliver daily, weekly, and monthly news summaries using LLMs and real-time tools. Designed for ease of extension, clean code, and flexible deployment.

> 📁 **Repository:** `Agentic_AI_Project3_End_To_End_AI_News_Summarizer`

---

## 🚀 Project Highlights

- 🗞️ **AI News Summarization:**  
  Automatically summarizes news articles into daily, weekly, and monthly digests.
- 🤖 **Agentic AI Approach:**  
  Modular nodes and graph structure for extensibility (easily add new tasks or sources).
- 🌐 **Web Search Tool:**  
  Fetches live news and information for up-to-date summaries.
- 📅 **Prebuilt Digests:**  
  See `AINews/daily_summary.md`, `AINews/weekly_summary.md`, `AINews/monthly_summary.md` for generated summaries.
- 🧩 **Extensible:**  
  Add new nodes/tools for more sources, languages, or summarization strategies.

---

## 🧠 Technical Stack

- **Python 3.13+**
- **Agentic AI Patterns**
- **LangGraph-inspired graph orchestration**
- **LLMs for summarization**
- **Modular agent, node, state, and tool abstractions**

---

## 🏗️ Project Structure

```bash
Agentic_AI_Project3_End_To_End_AI_News_Summarizer/
├── app.py                             # Main entry point
├── requirements.txt
├── LICENSE
├── README.md
├── AINews/
│   ├── daily_summary.md
│   ├── weekly_summary.md
│   └── monthly_summary.md
└── src/
    ├── __init__.py
    ├── langgraphagenticai/
    │   ├── __init__.py
    │   ├── LLMS/
    │   │   ├── __init__.py
    │   │   └── groqllm.py
    │   ├── graph/
    │   │   ├── __init__.py
    │   │   └── graph_builder.py
    │   ├── nodes/
    │   │   ├── __init__.py
    │   │   ├── ai_news_node.py
    │   │   ├── basic_chatbot_node.py
    │   │   └── chatbot_with_Tool_node.py
    │   ├── state/
    │   │   ├── __init__.py
    │   │   └── state.py
    │   ├── tools/
    │   │   ├── __init__.py
    │   │   └── search_tool.py
    │   └── ui/
    │       ├── __init__.py
    │       └── main.py
    └── __pycache__/
```

---

## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Agentic_AI_Project3_End_To_End_AI_News_Summarizer.git
cd Agentic_AI_Project3_End_To_End_AI_News_Summarizer
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the summarizer
```bash
python app.py
```
or (if there is a UI):
```bash
python src/langgraphagenticai/ui/main.py
```

---

## 🧪 Example Usage

- **Daily, Weekly, Monthly Summaries:**  
  Check the `AINews/` folder for generated news digests.
- **Custom Summarization:**  
  Run the app and provide your own news sources or URLs for on-the-fly summarization.
- **Extend Easily:**  
  Add new nodes/tools for other sources or languages with minimal code changes.

---

## 🧩 Extensibility

- **Add More Sources:**  
  Build new tools/nodes for different news APIs.
- **Custom Summary Styles:**  
  Adjust node logic for tailored summaries (topic, sentiment, etc).

---

## 📚 Documentation

See comments in source files and graph/nodes for extension details.

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **GPL-3.0 License** – see the LICENSE file for details.

---

#### Key Features:
1. Agentic, graph-based AI news summarization (daily/weekly/monthly)
2. Modular, clean, extensible Python codebase
3. Add more nodes, tools, or summary styles as needed
4. Designed for rapid research, learning, and real-world news digest pipelines
