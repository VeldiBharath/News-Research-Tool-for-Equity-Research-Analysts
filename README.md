# News-Research-Tool-for-Equity-Research-Analysts
A LLM Application made of Word Embeddings, Vector Database, Semantic search, LangChain, OpenAI and Streamlit

1. Word Embedding will allow us to find the relevant chunk of Information.
2. Vector Database allow us to find faster search on that database.
3. Then we give our prompt to OpenAI for answer.

![image](https://github.com/VeldiBharath/News-Research-Tool-for-Equity-Research-Analysts/assets/143754299/5a0051a1-5a03-4355-a543-7d4a7c4b959c)


## Technical Architecture
![image](https://github.com/VeldiBharath/News-Research-Tool-for-Equity-Research-Analysts/assets/143754299/b554837b-a3eb-416b-a9fa-42b17031b004)

## Project Structure
- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing your OpenAI API key.

 In this LLM project, we will use langchain, openai API, and streamlit to build a news research tool that can be used by equity research analysts to conduct their research. This end-to-end NLP project will give us a good experience in building a real-life industry project.

 WHy not use ChatGPT?
1. Copy pasting articles in ChatGpt is tedious. Professional analysts might not have much time in doing this.
2. We need a aggregate knowledge base. Some answers for questions might be  in different articles and chatgpt cant pull that for us.
3. Chatgpt has a 3000 word limit. We can supply huge article to chatgpt

## Features
- Load URLs or upload text files containing URLs to fetch article content.
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.

![image](https://github.com/VeldiBharath/News-Research-Tool-for-Equity-Research-Analysts/assets/143754299/c5c26cfd-a5e9-4a68-8bf6-5e190647e4e5)

#### Drawback : More LLM Calls

Credits : Codebasics


 
