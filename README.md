In this bot series of related documents are indexed by chunking them first, generating embeddings of the chunks, and indexing them into a vector store. At inference, the query is also embedded in a similar way.
The relevant documents are obtained by comparing the query against the indexed vectors, also denoted as “Relevant Documents”.

Generation: The relevant documents are combined with the original prompt as additional context. The combined text and prompt are then passed to the model for response generation which is then prepared as the final output of the system to the user.

We need the following ingredients:
1.A PDF as your knowledgebase
2.A requirements.txt file
3.An app.py file
4.An account on Hugging Face (See this blog to learn about building a LLM chatbot in Hugging Face)
