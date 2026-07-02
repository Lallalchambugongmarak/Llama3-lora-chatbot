# Llama3-lora-chatbot
# Llama-3-8B-LoRA-Finetune-Unsloth

Fine-tuned Llama-3 8B using LoRA for domain-specific chatbot.

**Key Results**
- 4-bit QLoRA with Unsloth: 75% VRAM reduction
- 1231 training steps on T4 GPU  
- 54MB adapter size vs 16GB base model
- <2s inference latency

**Stack**: PyTorch, Unsloth, PEFT, Transformers, BitsAndBytes, CUDA

**Training**: Google Colab T4 | **Inference**: 4-bit, <2GB VRAM
