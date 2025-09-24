# InsuranceClaims-RAG-AI
An AI-powered assistant for the insurance industry that can process claims, policies, reports, and client communications stored in multiple formats (PDF, Word, PowerPoint).

💡 Why It Matters

Insurance companies deal with vast amounts of unstructured data spread across claim forms (PDFs), policy documents (Word), and board presentations (PowerPoint). Agents and analysts waste hours searching through files to answer customer queries, check compliance rules, or validate claim histories.

This project solves that problem by:

Ingesting and indexing multi-format insurance documents.

Splitting, embedding, and storing them in a vector database.

Allowing retrieval-augmented queries such as:

What is the deductible for policy number XYZ?

How did claim patterns change between Q1 and Q2?

What exclusions are mentioned in John Doe’s auto policy?

insurance-claims-rag-ai/
│
├── README.md                # Project description & business use case
├── requirements.txt         # Dependencies
├── data/                    # Example insurance documents
│   ├── Claims/
│   │   ├── claim_form1.pdf
│   │   └── claim_form2.pdf
│   ├── Policies/
│   │   ├── auto_policy.docx
│   │   └── home_policy.docx
│   └── Reports/
│       └── Q1_trends.pptx
│
├── src/
│   ├── loaders.py           # PDF/DOCX/PPTX loaders with metadata
│   ├── splitter.py          # Text splitter config
│   ├── embeddings.py        # HuggingFace embeddings
│   ├── vectorstore.py       # Chroma vector store
│   └── qa.py                # Query function with context answers
│
└── notebooks/
    └── insurance_rag_project.ipynb   # project notebook


InsuranceClaims-RAG-AI is a Retrieval-Augmented Generation pipeline designed for the insurance sector.
It allows insurers, brokers, and agents to search across claims, policies, and compliance documents in natural language.

By combining document loaders, text splitting, HuggingFace embeddings, and ChromaDB, this project demonstrates how AI can:

Automate claim validation workflows

Improve customer service response times

Provide compliance-ready answers from internal policies

Turn raw documents into a searchable knowledge base

This repository showcases my ability to design production-ready AI/ML solutions for real-world industries, integrating document processing, retrieval, and LLM-driven Q&A.
