# A Proposed RAG Architecture

This is a RAG application for analysis of a company's documents using open source model , developed with LlamaIndex and Mistral 7B.


## Prerequisites
- Python version 3.8 or higher
- matplotlib
- langdetect
- spacy
- llama-index
- llama-index-embeddings-huggingface
- deepeval
- chromdb
- llama_index.vector_stores.chroma
- llama_index.llms.huggingface

## Setup

1. **Clone the repository:**

    ```sh
    cd ConversationalAI_RAG
    ```

2. **Create a virtual environment:**

    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    - On Windows:

        ```sh
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```sh
        source venv/bin/activate
        ```

4. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
      ```

4. **LLM Gauirral:**

Optional: In case you want to run the gaurdrail on Jupyter,you may want to install the guardrails-ai as per this page: https://docs.confident-ai.com/docs/getting-started. You also need to configure this package with a token that can be provided by signing up to their hub page. this can enable your access to download their modules such as toxicity, etc.

## Project Structure

- `notebook.ipynb`: Main Jupyter notebook
- `data`: The folder with sample documents
- `requirements.txt`: List of required Python packages.

## License

This project is licensed under the MIT License.