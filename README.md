
# FinEquityBot: Financial and Equity News Research Tool 

FinEquityBot is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.

![](FinEquityBot.jpg)

## Features

- It lets you load URLs or upload text files containing URLs to fetch the article content.
- This Bot will process article content through LangChain's UnstructuredURL Loader
- Next it lets you construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- You can interact with this Bot by inputting queries and receiving answers along with source URLs.


## Installation

1.Clone this repository to local machine using:

2.Navigate to the project directory:

3. Install the required dependencies using pip:

4.Set up your OpenAI API key by creating a .env file in the project root and adding your API

5. Run the Streamlit app:
```bash
streamlit run main.py

```

6.The web app will open in your browser.

- On the sidebar, you can input URLs directly.

- Initiate the data loading and processing by clicking "Process URLs."

- Observe the system as it performs text splitting, generates embedding vectors, and efficiently indexes them using FAISS.

- The embeddings will be stored and indexed using FAISS, enhancing retrieval speed.

- The FAISS index will be saved in a local file path in pickle format for future use.
- One can now ask a question and get the answer based on those news articles


## HAPPY EXPERIMENTING