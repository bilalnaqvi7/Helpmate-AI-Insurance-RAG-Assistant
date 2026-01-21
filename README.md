# HelpMate AI — Insurance Policy Q&A Assistant (RAG + LLM)

## Overview
HelpMate AI is a Retrieval-Augmented Generation (RAG) based assistant built to simplify complex insurance policy documents by enabling users to ask natural-language questions and receive structured, citation-backed answers from multiple policy PDFs.

## Problem Statement
Insurance policy documents are lengthy and difficult to interpret. Users struggle to quickly find coverage details, claim documentation requirements, grace periods, exclusions, and eligibility rules across multiple policy files.

## Objective
- Build a document-aware AI assistant that answers policy queries using retrieved context
- Provide grounded responses with supporting evidence and citations
- Improve customer experience by reducing manual document search time

## Solution (RAG Pipeline)
1) Ingest multiple insurance policy PDFs
2) Chunk & embed document text
3) Retrieve top relevant chunks for a user query
4) Generate a final answer grounded in retrieved evidence
5) Display citations / source references for trust & explainability

## Key Features
- Multi-document policy search across HDFC Life insurance PDFs
- Question answering with evidence-backed citations
- Retrieval debugging outputs (distance scores + retrieved chunks)
- Structured responses for real-world insurance queries

## Sample Queries (Outputs)
- "What types of coverage does this policy include?"
- "What documentation is required when filing a claim?"
- "What happens if I miss a payment?"

Screenshots:
- `outputs/query-results/Query1.png`
- `outputs/query-results/Query2.png`
- `outputs/query-results/Query3.png`

Retrieval debugging:
- `outputs/retrieval-debug/search1.png`
- `outputs/retrieval-debug/search2.png`
- `outputs/retrieval-debug/search3.png`

## Impact (Action → Outcome)
- Built an end-to-end RAG assistant to reduce policy lookup friction by enabling instant Q&A over long-form insurance PDFs.
- Improved response trust by grounding outputs in retrieved policy text and displaying citations.
- Enabled multi-policy comparisons by retrieving evidence from multiple documents instead of a single file.
- Added retrieval visibility via similarity distances and retrieved chunk previews for explainability and debugging.

## Tech / Tools
- Python
- LLM-based Question Answering
- Retrieval-Augmented Generation (RAG)
- Embeddings + Vector Similarity Search
- PDF Text Extraction
- Prompt Engineering
- Jupyter Notebook

## Repository Contents
- Project Report: `docs/Project_Report_HelpMate_AI_Syed_Mohammad_Bilal_Simplifying_Insurance_Document_via_RAG.pdf`
- Notebook Code: `notebooks/Code_Solution_HelpMate_AI_RAG.ipynb`
- Policy PDFs: `datasets/policy-documents/`
- Output Screenshots: `outputs/`
