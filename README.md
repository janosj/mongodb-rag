# Atlas Vector Search with RAG (slightly modified)

A simple Question Answering demonstration app that illustrates the utility of a Retrieval Augemented Generation framework. The application front-end is built with Python and Gradio. The underlying RAG framework is implemented with LangChain, OpenAI models, and MongoDB Atlas Vector Search. 

## Credits

This repo is based almost entirely on the work of Harshad Dhavale. His original blog ("RAG with Atlas Vector Search, LangChain, and OpenAI") can be found [here](https://www.mongodb.com/developer/products/atlas/rag-atlas-vector-search-langchain-openai/), and his original repo [here](https://github.com/mongodb-developer/atlas-vector-search-rag). I've only added some convenience scripts for running the demo as well as made some minor improvements to the UI to include what sort of results you get when you rely solely on an LLM without providing the necessary context obtained by Vector Search. 

## Setting and Launching the Demo

Full details can be found in the original blog post. Convenience scripts have been added to make things slightly easier. See the setup notes for a concise summary. 


