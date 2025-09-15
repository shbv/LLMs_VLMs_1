# Overview
- This repo goes over some of the key concepts & code examples of GenAI Language & Vision models (LLMs, VLMs).

# What is it for?
- The goal is to have a simple reference code & notes to review these concepts.
- I used knowledge from various sources & my work experience to review these concepts. References will be listed along with code/notebooks.
- This will not include any proprietary code that I worked on for my companies.

# Some details
- It has the reference codes to run training/inference on LLMs/VLMs. It shows how to:
    - Use Huggingface library to train, finetune or run inference
    - Use LLM/VLM APIs like ChatGPT
    - Use Pytorch to define key components of LLMs/VLMs from scratch. Define models like GPT2 & Llama3.*.  Train them to predict next token & later finetune them for downstream tasks like classification or to follow instructions.

# Key directories here
    - `hf_api_notebooks`: All the notebooks on how to use Huggingface library or APIs
    - `pytorch_from_scratch_notebooks`: All the notebooks on how to use Pytorch from scratch to define & train LLMs
    - `pytorch_from_scratch_llm_code`: All the LLM code organized in modular form
    - `misc_notebooks`: Miscellaneous notebooks
    - `data`: Datasets are to be stored here. (Omitted large files to avoid git repo bloat)
    - 'output_dir`: Models & training outputs are saved here. (Omitted from checkin to avoid git repo bloat)