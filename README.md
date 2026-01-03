# medical-chatbot
This project implements a medical question-answering chatbot using large language models (LLaMA-2 and BioMistral) for symptom-based disease prediction. 
The system explores retrieval-augmented generation (RAG) by grounding LLM responses in a structured medical knowledge base using dense text embeddings. In parallel, supervised fine-tuning with LoRA is implemented to compare performance trade-offs between retrieval-based inference and domain-adapted generation.  
The project is built using PyTorch and Hugging Face Transformers and focuses on data preprocessing, tokenization, model fine-tuning, and hallucination reduction in medical LLM applications.
