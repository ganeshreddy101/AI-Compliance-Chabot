# AI-Compliance-Chabot

An LLM-powered chatbot that helps companies, startups, and individuals understand and comply with AI regulations across different countries by querying official policy PDFs in natural language.

This project is highly relevant for companies deploying AI systems that must meet legal and ethical standards across countries. Manual compliance reviews are expensive and slow. My chatbot solves this by turning static policy PDFs into an interactive knowledge assistant — reducing risk and saving legal team costs.

## Project Summary

This chatbot allows users to upload one or multiple AI policy/regulation PDFs (e.g., India’s Responsible AI policy, EU AI Act, US Executive Orders), ask compliance-related questions, and receive concise, sourced responses powered by LLMs + RAG. It eliminates the need for manual reading of long policy documents by legal teams and helps prevent fines or violations due to non-compliance.

## Features

- Upload one or multiple AI policy PDFs.
- Ask questions in plain English (e.g., "What are the penalties for misuse of AI in the EU?").
- Uses LangChain + FAISS for document retrievAL.
- Displays the exact source paragraph from the document.
- Supports multi-turn conversations.
- Powered by flan-t5-large using Hugging Face Transformers.
- Built with Streamlit for clean, responsive UI.

## Tech Stack
This project uses the following technologies:
- Streamlit to build the user-friendly web interface.
- LangChain for implementing the Retrieval-Augmented Generation (RAG) pipeline and managing conversation memory.
- FAISS (Facebook AI Similarity Search) to perform vector-based document retrieval.
- Hugging Face Transformers, specifically the flan-t5-large model, as the core language model for generating answers.
- Sentence Transformers (all-MiniLM-L6-v2) to convert text chunks into semantic embeddings for similarity search.
- PyPDFLoader to extract and split content from uploaded PDF policy documents.


![image alt](https://github.com/ganeshreddy101/AI-Compliance-Chabot/blob/95838eab7d73d35b1230a851ae2466ba55f23634/chatbot%20file%20upload.png)

![image alt](https://github.com/ganeshreddy101/AI-Compliance-Chabot/blob/4543e4081028ea17f8cc622ec21607f2d298320e/chatbot%20history.png)




## Example Questions to Ask:
- “What are the penalties under the EU AI Act?”
- “What are India’s 7 principles for responsible AI?”
- “Does the US Executive Order require risk assessments?”
- “Can startups use facial recognition in the UK?”


## Supported Policy PDFs (examples):

- **India:** Responsible AI for All – NITI Aayog
- **USA:** Executive Order 14179, NIST AI RMF
- **EU:** AI Act (2024)
- **UK:** AI Regulation White Paper (2023)
- **Australia:** Automation & AI Strategy (2025)

## Use Cases:
- AI Startups: Stay compliant with country-specific AI laws
- Legal Teams: Save time analyzing long policy documents
- Researchers: Instantly query legal frameworks in AI governance
- MNCs: Ensure global compliance across regional offices

## Conclusion:
The AI Compliance Chatbot is a practical and impactful solution for navigating the complex landscape of AI regulations across countries. By combining the power of LLMs, semantic search, and document intelligence, this chatbot enables companies, startups, and professionals to ask plain-language questions and get accurate, sourced answers from official AI policy documents. It significantly reduces manual effort, legal consultation time, and the risk of regulatory non-compliance — making it a valuable tool for any organization building or using AI responsibly.

This project also demonstrates my ability to:
- Build full-stack AI apps using modern tools like LangChain, Hugging Face, and Streamlit
- Apply RAG-based architectures to real-world business problems
- Create user-focused solutions with clean UI and multi-country flexibility
