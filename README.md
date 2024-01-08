# AI-Human-Generated-Program-Code-Dataset
This is the repository of the "AI/Human-Generated Program Code Dataset", introduced in the paper "Program Code Generation with Generative AIs".

# Notes
- Prompts of Chatbots are formulated like a chat message
- Prompts of IDE Extensions are formulated as `docstrings` plus the class name and method name of the asked solution as the results need to have a specific class name and method name to be able to be submitted on LeetCode
- Prompts of InstructCodeT5+ are written in Python beginning with `prompt="""` as the interferrence with this AI took place via Google Colab and Huggingface Library
- The dataset is available in two different variants (JSONL and CSV), pick the one you prefer.
