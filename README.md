The Llama2 model is used to scrape data like project, title, description,
status,date, currency,sector etc for the given url in the python script.
Steps involved in the project:
1. Import the necessary modules from the Langchain library.
2. Load the required modules for processing and embedding the text.
3. Define the text to be processed and split it into chunks using a text splitter.
4. Create embeddings for the chunks using HuggingFace embeddings.
5. Build a FAISS vector index from the embeddings.
6. Store the vector index in a local file.
7. Load the stored vector index from the file.
8. Define a retrieval question-answering chain using Langchain, specifying the
LLMS model and the vector index as retriever.
9. Define a query to extract specific information from the provided text.
10. Execute the retrieval question-answering chain and extract the answer text.
