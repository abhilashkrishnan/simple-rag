# Simple RAG
## A Simple Retrieval Augmented Generation (RAG) Framework

#### Retrieval-Augmented Generation (RAG) enhances language models by integrating external knowledge sources, improving their ability to provide accurate and up-to-date information. A basic RAG system comprises two main components:

#### Retrieval Model: 
  - Fetches relevant information from external sources like databases or search engines.
#### Language Model: 
  - Generates responses based on the retrieved information.
 
To build a simple RAG system in Python using the ollama library, follow these steps:

**1. Indexing Phase**

**Chunking:** Divide your dataset into smaller segments (e.g., sentences or paragraphs).
**Embedding:** Convert each chunk into a vector representation using a pre-trained embedding model.
**Storage:** Store these embeddings in a vector database for efficient retrieval.

**2. Retrieval Phase**
   
**Query Embedding:** Convert the user's query into an embedding.
**Similarity Search:** Compare the query embedding with stored embeddings to find the most relevant chunks using metrics like cosine similarity.

**3. Generation Phase**

**Prompt Construction:** Combine the retrieved information with the user's query to form a prompt.
**Response Generation:** Use a language model to generate a response based on this prompt.

This is a basic RAG system that retrieves relevant information from a dataset and generates responses accordingly. For more advanced implementations, consider exploring modular RAG systems that incorporate routing, scheduling, and fusion mechanisms to create flexible and reconfigurable frameworks.

