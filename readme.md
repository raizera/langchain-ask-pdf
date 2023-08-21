# Langchain Ask PDF (Tutorial)

Learn how to harness the power of Langchain, an open-source Python (and Javascript) framework, to create intelligent applications. Discover Langchain's capabilities in training GPT models on your data and generating personalized LLMs. Explore text embeddings and their integration with Langchain using OpenAI's API.

In this tutorial, we'll guide you through building a fully functional Streamlit application. Train GPT on PDF documents and fine-tune it to your specific use case. Experience the seamless user interface as you upload PDFs, ask questions, and receive prompt answers from the LLM.

Unleash Langchain's versatility in chatbots, document analysis, and more. Automate tasks and improve efficiency using Langchain with Streamlit.

Take your natural language processing skills to the next level. Start building powerful applications with Langchain today!

## How it works

The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response.

The application uses Streamlit to create the GUI and Langchain to deal with the LLM.


## Installation

To install the repository, please clone this repository and install the requirements:

```
pip install -r requirements.txt
```

You will also need to add your OpenAI API key to the `.env` file.

## Usage

To use the application, run the `main.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run app.py
```


## Contributing

This repository is for educational purposes only and is not intended to receive further contributions. It is supposed to be used as support material for the YouTube tutorial that shows how to build the project.


