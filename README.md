# Exploration-of-NLP-Tasks-with-LLAMA2
This project utilizes the Llama 2 language model via the llama2.cpp interface to perform various NLP tasks such as text summarization, translation, and question answering. It provides code examples and prompts for experimentation with different models and parameter settings.

This notebook explores Natural Language Processing (NLP) tasks using the Llama 2 language model and the llama2.cpp interface. It leverages Google Colab's T4 GPU for faster processing.

The notebook covers:

Setting up the environment: Installing llama-cpp-python and huggingface_hub.
Choosing a Llama 2 model: Selecting "TheBloke/Llama-2-13B-chat-GGML" for this project.
Downloading the model: using hf_hub_download.
Running inference: Setting up the Llama object from llama_cpp for both GPU and CPU.
Example prompts: Demonstrating code generation and natural language generation with zero-shot prompts.
NLP tasks: Provides prompts and code for users to experiment with:
- Natural language generation (recipe)
- Summarization (Wikipedia article)
- Machine translation (Marathi)
- Named entity recognition (JSON output)
- Dialogue act tagging (JSON output)
