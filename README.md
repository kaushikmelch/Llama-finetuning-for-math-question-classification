---
base_model: unsloth/meta-llama-3.1-8b-bnb-4bit
library_name: peft
---

# Finetuning Llama3-8B to predict correctness of answers to math questions
This project involves the Supervised-Fine Tuning(SFT) of Llama3-8B model to predict the correctness of answers to math questions.
The goal is to assess whether the provided answer to each question is correct or not. 

## Features
- Lightweight fine-tuning using LoRA.  
- Custom tokenizers and dataset preprocessing.  
- Seamless integration with Weights and Biases (WandB) for tracking training and evaluation metrics.  
- High accuracy and low validation loss on fine-tuned tasks.

### Team
Kaushik Mellacheruvu

Srirama Bulusu
(New York University)