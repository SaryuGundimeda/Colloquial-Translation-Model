# Colloquial-Translation-Model
A transformer-based model fine-tuned for translating English sentences into colloquial Hindi. Built using the Helsinki-NLP/opus-mt-en-hi model and a custom dataset of informal phrases.

This project was developed as a submission for the Sawit.AI Hackathon (2025), focusing on solving real-world language challenges using NLP. It is a fine-tuned transformer model designed to translate English sentences into colloquial Hindi, capturing the informal tone and expressions used in daily conversations.

Project Summary
- Built a custom parallel dataset of English sentences and their Hindi colloquial counterparts.
- Fine-tuned the Helsinki-NLP/opus-mt-en-hi model using Hugging Face Transformers.
- Evaluated model performance on unseen data using expected outputs and accuracy.
- Packaged and deployed the model for real-time translation and research use.

Model Details
- Base Model: Helsinki-NLP/opus-mt-en-hi
- Framework: PyTorch + Hugging Face Transformers
- Training Data: Custom parallel dataset of colloquial English-Hindi pairs
- Training Type: Supervised fine-tuning

Intended Use

This model is designed for:
- NLP researchers working on informal and code-mixed language understanding.
- Applications needing real-time translation with a conversational tone (e.g., chatbots, regional assistants).
- Language learners and education tools focusing on natural, everyday Hindi.

Out of Scope
- Not suitable for formal translation (e.g., legal, academic, or medical domains).
- May not handle highly idiomatic or regional dialects outside of North Indian Hindi.
- Should not be used for hate speech, offensive content generation, or deepfake translation.

Sawit.AI Hackathon

This model was created for the Sawit.ai Hackathon to improve machine understanding of informal, real-world Hindi conversations, especially as used in podcasts, social media, and daily speech.
