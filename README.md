# Langchain Examples

## Description
This repository contains notebooks to serve as examples for using [Langchain](https://python.langchain.com/en/latest/getting_started/getting_started.html). 

## Dependencies
To run these notebooks, you will need the libraries listed in `requirements.txt`. Install these using pip by entering the command `pip install -r requirements.txt`

You will also need API keys for [OpenAI](https://platform.openai.com/docs/api-reference) and [SERP](https://serpapi.com/). To run the notebook without any changes, save these keys to "openai-api-key.txt" and "serp-api-key.txt" in the same directory. Alternatively, you can enter the keys into your notebook manually.

## Notebooks
 
### Basic Examples
`LangChain.ipynb` contains the basic examples listed in Langchain's "Getting Started" guide. Use this notebook if you just want an overview of what you can do with LangChain.

### Question Answering over Documents
`LangchainQA.ipynb` contains examples for asking an LLM questions about a document or set of documents. Use this notebook if you want a deeper dive into analyzing documents. This notebook requires that you also have the `/research_papers` directory and `state_of_the_union.txt`.

### Asking Questions about Code
`LangchainAnalyzeCode.ipynb` is an example of using Langchain to analyze a code base (in this case, the LangChain code base). To run this notebook, you will need to fork and download the [LangChain Repository](https://github.com/hwchase17/langchain) and save the path in the notebook accordingly. Use this notebook if you would like to ask an LLM questions about code, or to ask it to create code examples using a specific code base.

