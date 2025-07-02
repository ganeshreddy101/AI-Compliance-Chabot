# AI-Compliance-Chabot

An LLM-powered chatbot that helps companies, startups, and individuals understand and comply with AI regulations across different countries by querying official policy PDFs in natural language.

This project is highly relevant for companies deploying AI systems that must meet legal and ethical standards across countries. Manual compliance reviews are expensive and slow. My chatbot solves this by turning static policy PDFs into an interactive knowledge assistant — reducing risk and saving legal team costs.

Project Summary:

This chatbot allows users to upload one or multiple AI policy/regulation PDFs (e.g., India’s Responsible AI policy, EU AI Act, US Executive Orders), ask compliance-related questions, and receive concise, sourced responses powered by LLMs + RAG. It eliminates the need for manual reading of long policy documents by legal teams and helps prevent fines or violations due to non-compliance.

Features:

~ Upload one or multiple AI policy PDFs

~ Ask questions in plain English (e.g., "What are the penalties for misuse of AI in the EU?")

~ Uses LangChain + FAISS for document retrieval

~ Displays the exact source paragraph from the document

~ Supports multi-turn conversations

~ Powered by flan-t5-large using Hugging Face Transformers

~ Built with Streamlit for clean, responsive UI

Tech Stack:

TOOL	                          PURPOSE

Streamlit	                      UI framework

LangChain	                      RAG pipeline and memory

FAISS	                          Vector similarity search

Transformers (Hugging Face)	    LLM backend (flan-t5-large)

Sentence Transformers	          Embeddings: all-MiniLM-L6-v2

PyPDFLoader	                    PDF parsing


Example Questions to Ask:

“What are the penalties under the EU AI Act?”

“What are India’s 7 principles for responsible AI?”

“Does the US Executive Order require risk assessments?”

“Can startups use facial recognition in the UK?”


Supported Policy PDFs (examples):

~ India: Responsible AI for All – NITI Aayog

~ USA: Executive Order 14179, NIST AI RMF

~ EU: AI Act (2024)

~ UK: AI Regulation White Paper (2023)

~ Australia: Automation & AI Strategy (2025)

Use Cases:

~ AI Startups: Stay compliant with country-specific AI laws

~ Legal Teams: Save time analyzing long policy documents

~ Researchers: Instantly query legal frameworks in AI governance

~ MNCs: Ensure global compliance across regional offices

