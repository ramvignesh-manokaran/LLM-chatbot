# Building A Chatbot
We'll go over an example of how to design and implement an LLM-powered chatbot. This chatbot will be able to have a conversation and remember previous interactions.

Note that this chatbot that we build will only use the language model to have a conversation. There are several other related concepts that you may be looking for:

- Conversational RAG: Enable a chatbot experience over an external source of data
- Agents: Build a chatbot that can take actions

We will cover the basics which will be helpful for those two more advanced topics.

## Setting Up environment

1.Run below command to create python environment
 ```bash
conda create -p venv python==3.10 -y  
```

2. Create requirements.txt file with required libraries.

3. Activate environment by running below command.
 ```bash
conda activate venv/ 
```
4. Install all libs in requirements.txt using below command.
 ```bash
pip install -r requirements.txt
```
5. Create an .env file with below keys before executing ipynb files. OPENAI_API_KEY="" LANGCHAIN_API_KEY="" LANGCHAIN_PROJECT="" GROQ_API_KEY=""