# Overview
- This repo has concepts & reference codes to run training/inference on LLMs/VLMs. It shows how to:
    - Use Pytorch to define LLMs/VLMs & their components from scratch. 
        - Define models like GPT2 & Llama3.*.  
        - Train them to predict next token 
        - Finetune them for downstream tasks like:
            - Classification.
            - Follow instructions.
    - Use Huggingface library to train/finetune LLMs, run inference on them.
    - Use LLM/VLM APIs like ChatGPT

# Key directories here
- `pytorch_from_scratch_toy_model_code`:
    - Toy neural network training using single & mutiple GPUs
- `pytorch_from_scratch_notebooks`: 
    - Notebooks using Pytorch from scratch to define LLM components
- `pytorch_from_scratch_llm_code`: 
    - Modular code to define & perform LLM pre-training, fine-tuning from scratch in Pytorch
    - Includes models like GPT2 & Llama3.*. 
- `hf_api_notebooks`: 
    - Notebooks using Huggingface library or APIs to tasks like
        - Perform fine-tuning
        - Run inference
        - Use LLM/VLM APIs like ChatGPT, etc.
        - LLM as judge etc.
- `pytorch_from_scratch_vlm_code`
    - Example training / fine-tuning / inference on 
        - Small VLM - `nanoVLM`
        - Large VLM - `Aria`
- `misc_notebooks`: 
    - Miscellaneous notebooks
- `data`: 
    - Datasets are to be stored here. (Omitted large files to avoid git repo bloat)
- `output_dir`: 
    - Models & training outputs are saved here. (Omitted from checkin to avoid git repo bloat)

### Note:
- The goal is to have a simple reference code & notes to review these concepts.
- I used knowledge from various sources & my work experience to review these concepts. 
- References will be listed at appropriate places (along with code/notebooks or in README).