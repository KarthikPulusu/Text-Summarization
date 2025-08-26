# Text-Summarization
This Text Summarization uses Hugging Face LLaMA-2 with LangChain for summarization. It loads large text files, splits them into chunks, and then applies a summarization prompt via a HuggingFace pipeline.

Project Overview

This project demonstrates automatic text summarization using LLaMA-2 (7B) integrated with LangChain. It loads large documents, splits them into manageable chunks, and generates concise summaries highlighting only the key points.

🔹 Features

Uses Hugging Face Transformers with meta-llama/Llama-2-7b-chat-hf.
LangChain pipeline for managing prompts and chaining summarization tasks.
Splits large documents into overlapping chunks for better context preservation.
Generates clear, concise summaries focused on the main ideas.

🔹 Tech Stack 

Python
Transformers (Hugging Face)
LangChain
PyTorch

🔹 Workflow

Load a large text file.
Split text into overlapping chunks using RecursiveCharacterTextSplitter.
Use LLaMA-2 with a summarization prompt to condense text.
Combine results into a final structured summary.

🔹 Learning Outcomes

Hands-on with LangChain prompt engineering.
Handling large text inputs with chunking.
Deploying state-of-the-art LLMs for NLP tasks.
Improved understanding of summarization pipelines in real-world ML workflows.
