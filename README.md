# production-RAG

**ReadMe** (#TODO - Documentation to be updated)

An end to end RAG application
following are the components that are used to create this application.


*   **Retrieval**
      - OpenAI, huggingface* with *Pinecone* as vector database
*   **Generation**
      - Groq, Llama3
*   **Monitoring**
      - Langsmith
*   **Guardrails**
      - Nemo-guardrails
*   **Orchestration**
      - Langchain

![image](https://github.com/user-attachments/assets/a1bf4183-4320-4815-b37a-86685f20e2b4)


you also need to create a folder `config` and following files in it
1. `config.yml`
2. `prompts.yml`

files are added in the repository.
these files are used by guard rails to place some pre-requisite checks
over the input query.
