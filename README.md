# LangChain---Chat-With-Search

### Streamlit App link  
https://langchain---chat-with-search-anmsgtjudutt3n7vpnetjw.streamlit.app/

This repository contains a Streamlit-based chatbot application that utilizes LangChain and Groq's Llama 3 model to answer user queries with real-time web searches. The chatbot integrates Wikipedia, Arxiv, and DuckDuckGo search functionalities to provide accurate and relevant responses.

### Features

> Conversational Chatbot: Uses LangChain with Llama 3 for intelligent conversations.

> Web Search Integration: Fetches real-time information from Wikipedia, Arxiv, and DuckDuckGo.

> Streamlit UI: Interactive and user-friendly interface.

> API Key Input: Securely enter your Groq API key through the sidebar.

> Streaming Responses: Provides real-time responses for an interactive experience.

## Installation

### Prerequisites

Ensure you have Python installed. You can download it from ```python.org.```

### Clone the Repository
```
git clone https://github.com/Aayush212/langchain-chat-with-search.git
cd langchain-chat-with-search
```

### Install Dependencies

Create a virtual environment (optional but recommended) and install the required Python packages:
```
pip install -r requirements.txt
```

### Set Up Environment Variables

Create a ```.env``` file and add your Groq API key:
```
GROQ_API_KEY=your_groq_api_key_here
```

## Usage

Run the Streamlit app using:
```
streamlit run app.py
```

### How It Works

> The user enters a query in the chat interface.

> The chatbot uses the Groq-powered Llama 3 model to process the input.

> The system searches relevant information from Wikipedia, Arxiv, and DuckDuckGo.

> The chatbot returns a well-structured response.

### Dependencies

```streamlit```

```langchain```

```langchain_groq```

```langchain_community```

```python-dotenv```

### Contributing

Feel free to fork the repository and submit pull requests to improve the project.

### License

This project is licensed under the MIT License.

### Acknowledgments

> LangChain

> Streamlit

> Groq



