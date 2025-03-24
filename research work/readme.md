##What is RAG?

Retrieval-Augmented Generation (RAG) is a popular technique that enhances LLM responses by retrieving relevant external knowledge from a knowledge base before generating an answer. RAG improves accuracy, reduces hallucinations, and allows the model to provide more contextually relevant and up-to-date information.

RAG involves three steps namely: Retrieval, Augmentation and Generation.

Retrieval - In this step, the system searches an external knowledge source, such as a vector database to find relevant information based on the user query.

Augmentation - The retrieved information is then combined with the original user query to get the LLM prompt.

Generation - The LLM processes the prompt and generates a response, integrating both its pre-trained knowledge and the retrieved information. This results in more accurate and contextually relevant responses.
Let us understand RAG with a simple example.
https://github.com/KalyanKS-NLP/rag-zero-to-hero-guide/blob/main/RAG%20Basics/images/What_is_RAG.gif


