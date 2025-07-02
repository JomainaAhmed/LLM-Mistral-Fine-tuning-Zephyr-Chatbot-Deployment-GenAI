# LLM-Mistral-Fine-tuning-Zephyr-Chatbot-Deployment-GenAI
Designed the full training pipeline using HuggingFace transformers and datasets and implemented LoRA adapters for efficient finetuning

Finetuning Mistral-7B using QLoRA for memory-efficient performance, and deploying a Zephyr-based chatbot with conversation memory and fast inference.

🛠 Tech Stack: Python · HuggingFace Transformers · QLoRA · Mistral-7B · Zephyr · LoRA · BitsAndBytes

💡 Features:

4-bit quantized training pipeline using QLoRA + LoRA adapters

Trained on 1.5k+ prompt-response pairs for conversational modeling

Deployed Zephyr chatbot with memory and <700ms latency (manual benchmark)

Custom model loading, prompt formatting, and memory handling

Ideal Usage: Demonstrates fine-tuning for lightweight LLM deployment with fast inference and retention.
