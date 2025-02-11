Just a proof of concept project, not a complete application. 

The scope is to generate an agent capable of matching the users house preferences to an already generated house description.

1. Generate with an LLM a dataset of luxury house listings providing house descriptions in a form of advertisement.
2. On continue I use 2 options for vector database (ChromaDB and FAISS) to store the embeddings and test a similarity search capability
3. Finally I am creating an LLM agent that is given an analytical prompt and tries to match the user preferences to one of the generating listings. The agent should also provide explanation and the logic used to derive the result.
