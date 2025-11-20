# Langflow-Project

Building an end-to-end generative AI applications using IBM watsonx.ai, DataStax Astra DB, and Langflow workflows.

Three workflows :- a Foundational AI assistant, a Retrieval-Augmented Generation (RAG) pipeline, and an Agentic AI System

Langflow is a visual orchestration tool for building AI applications.

# Flows

**Basic Chatbot workflow** :

This basic chatbot establishes a simple AI assistant using IBM watsonx.ai. A chat input feeds into the model, processed through a prompt component, and returns output. This introduces the fundamentals of prompt engineering and foundation model usage.

<img width="907" height="525" alt="Pasted Graphic" src="https://github.com/user-attachments/assets/f85fa768-1943-4ef3-9364-0a93c37a9d05" />

**RAG workflow** : 

RAG enhances responses by grounding them in external data stored in Astra DB. Documents are ingested and vectorized as embeddings. A retriever component fetches relevant information, which the LLM incorporates in real time.

<img width="1113" height="667" alt="Pasted Graphic 1" src="https://github.com/user-attachments/assets/558e1499-0833-4e8e-a69f-604c42f99cbe" />

**Agentic AI Flow** :

This workflow demonstrates an agentic system capable of autonomous reasoning and tool-driven actions. Unlike simple chat assistants, agentic AI can sequence tasks, call external tools, and adapt its decisions based on user goals and available resources.

<img width="1279" height="847" alt="Pasted Graphic 2" src="https://github.com/user-attachments/assets/ce02b52b-33ee-49bc-a156-792c654e4130" />

Through Langflow’s visual interface, IBM watsonx.ai’s powerful foundation models, and DataStax Astra DB’s vector capabilities, these workflows offer a practical and scalable approach to building intelligent, context-aware applications.
