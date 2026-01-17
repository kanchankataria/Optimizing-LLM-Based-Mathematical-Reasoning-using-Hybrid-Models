Optimizing LLM-Based Mathematical Reasoning using Hybrid Models

Project Overview
This project improves the reliability and efficiency of large language models on mathematical word problems using a hybrid two-stage approach. A fine-tuned LLaMA-3 model generates solutions, while a lightweight logistic regression model verifies confidence and selectively triggers re-generation.

Key Results (GSM8K)
- Baseline LLaMA-3 Accuracy: 76%
- Hybrid System Accuracy: 81% (+5% improvement)
- Reduced average inference time through selective computation

Tech Stack
Python, LLaMA-3, Hugging Face Transformers, Logistic Regression, LoRA (PEFT), Google Colab

Setup
1. Clone the repository
2. Install dependencies from requirements.txt
3. Set Hugging Face token using environment variables
4. Run notebooks in Google Colab or locally

Security Note
Hugging Face tokens are handled securely using environment variables and are not hard-coded in the repository.
