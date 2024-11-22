


### **README.md**

```markdown
# 🔎 LangChain Web Search Assistant

This project is an interactive chatbot powered by **LangChain** and **Groq models**, designed to assist users with real-time web searches, research queries, and contextual answers. The chatbot integrates **DuckDuckGo**, **Arxiv**, and **Wikipedia** APIs to provide accurate, reliable, and enriched responses.

## 🌟 Features
- **Conversational Interface**: Engage with the chatbot seamlessly through an intuitive Streamlit-powered interface.
- **Web Search**: Perform real-time searches using DuckDuckGo.
- **Research Papers**: Fetch summaries of academic papers from Arxiv.
- **Wikipedia Integration**: Retrieve concise information from Wikipedia.
- **Real-time Logs**: Visualize the agent's thought process and actions in the app.

## 🛠️ Technologies Used
- **LangChain**: For agent and tool orchestration.
- **Groq Language Model**: Used for response generation and reasoning.
- **Streamlit**: Provides the frontend for interactive user communication.
- **DuckDuckGo API**: For web search queries.
- **Arxiv API**: To fetch research paper summaries.
- **Wikipedia API**: For extracting information from Wikipedia.

## 🚀 How to Run the Project
### Prerequisites
1. Python 3.7 or higher installed.
2. Install required dependencies using `pip`.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/0Xuser100/LangChain-WebSearch-Assistant.git
   cd LangChain-WebSearch-Assistant
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your API keys:
   - Obtain your Groq API key and add it during app execution.

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

### Required Packages
Add the following dependencies to your `requirements.txt`:
```text
streamlit
langchain
langchain_groq
duckduckgo-search
python-dotenv
```

## 🧩 Project Structure
```
LangChain-WebSearch-Assistant/
├── app.py             # Main Streamlit app
├── README.md          # Documentation
├── requirements.txt   # Dependencies
└── .env.example       # Example environment variables file
```

## 📚 How It Works
1. **Conversation Handling**: 
   - The chatbot maintains a session state to track user interactions.
   - User messages and assistant responses are stored for context.

2. **Tool Integration**:
   - The agent uses:
     - DuckDuckGo for general web searches.
     - Arxiv for academic research summaries.
     - Wikipedia for general knowledge queries.

3. **Response Generation**:
   - Powered by Groq's **Llama3-8b-8192** model.
   - Generates thoughtful and contextual answers using external tool outputs.

## 🧪 Example Use Case
1. **User Query**: *"What is quantum computing?"*
2. **Assistant Response**:
   - Fetches related information from Wikipedia, Arxiv, and web search.
   - Combines and summarizes the findings in an easy-to-understand manner.

## 🤝 Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

## 📄 License
This project is licensed under the MIT License.

## 📞 Contact
For questions or suggestions, feel free to reach out to:
- **Name**: Mahmoud Abdelhamid
- **Email**: mahmoudabdulhamid22@gmail.com
- **GitHub**: [https://github.com/0Xuser100](https://github.com/0Xuser100)
- **LinkedIn**: [https://www.linkedin.com/in/mahmoud-abdulhamid-052244230/](https://www.linkedin.com/in/mahmoud-abdulhamid-052244230/)
---
