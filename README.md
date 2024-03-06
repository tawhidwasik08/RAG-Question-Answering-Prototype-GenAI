## Retrieval-Augmented Generation Question Answering Prototype with langchain

This repository contains a prototype Jupyter notebook showcasing Retrieval-Augmented Generation (RAG) for question answering. It demonstrates the following functionalities:

1. Document Retrieval:
  * Leverages the Chroma library to create a document vector database from PDF documents using pre-trained sentence embeddings from HuggingFace.
  * Utilizes cosine similarity search to retrieve relevant documents based on the user's question.

2. Question Answering with Offline LLM:
  * Integrates a pre-trained LLM model from HuggingFace for answer generation.
  * The retrieved document context is provided as input to the LLM, allowing it to generate answers based on the context.

3. Question Answering with OpenAI API:
   * Demonstrates interaction with the OpenAI API for accessing their GPT-3.5 language model for answer generation.
   * This option allows utilizing the capabilities of a powerful LLM through the API.

### Running the notebook
1. The notebook was created in colab. You can import it in colab, set up proper directories.
2. Or, set up a python venv, install the libraries mentioned at the start and run the notebook in Jupyter.

### Additional notes
This repository serves as a starting point for exploring and experimenting with RAG based question answering. You can explore further by:
* Implementing different retrieval strategies.
* Fine-tuning the LLM model on a specific question answering dataset.
* Integrating the prototype into a larger application.

Hope it helps anyone looking for simple external knowledge based conversational ai notebooks.
<br>Peace! ✌️


