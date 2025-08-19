# GenAI Class 4 - Cohort 1

In this class, we will be learning about building RAG(Retrieval Augmented Generation).

## Topics covered

1.  What it is RAG?
2.  Why RAG is used?
3.  What is indexing in RAG?
4.  What is reterival/chat in RAG?
5.  How RAG works (retriever + generator) with a simple example?

    - RAG Naive Solution
    - RAG Optimized Solution
    - RAG Highly Optimized Solution
      Even a simple RAG application requires fine-tuning multiple parameters, components, and models.

            Stage 1: Data Preparation (Indexing Phase)
                Step 1: Setup Raw Data Sources
                Step 2: Information Extraction (OCR, PDF data extraction, web crawlers, etc.)
                Step 3: Chunking
                Step 4: Embedding (make for sementic data)
                Step 5: Store Embedding into Vector Database

             Stage 2: Retrieval Augmented Generation (Reterival/chat Phase)
                 Step 6: User Input Query
                 Step 7: Create User Input Query Embedding
                 Step 8: Search Relavant Embedding from Vector Database
                 Step 9: Return the Relevant Data (vector embedding + chunks)
                 Step 10: Pass Relevant Data & User Input Query to Chat LLM(s)
                 Step 11: User Get the Final Output through LLMs

6.  Why we perform vectorization in RAG?
7.  Why RAGs exist?
8.  What is chunking and why we perform chunking?
9.  Why overlapping is used in chunking?
10. What is langchain and why is used?
11. What is vector database and why is used?
12. Build your own RAG (Retrieval-Augmented Generation) system in Node.js with two main phases: Indexing and Retrieval/Chat.

## Assignments

1. `Assignment 1:`RAG application website

Build a small RAG (Retrieval Augmented Generation) application to be used on a web browser

### Create a simple UI with:

- Data Source (TextArea) to enter text
- Upload option to upload files (e.g. PDF, CSV, etc)
- RAG Store where the data is indexed
- Chat window to ask queries from the stored data
- App should support both File upload and Website input as data sources.

## Blogs

1. `Blog 1:` Write an article about Retrieval Augmented Generation (RAG) on Hashnode
2. `Blog + Research:` Where RAGs Fail?

### Links to Blogs

- [Retrieval Augmented Generation (RAG)](https://bcapathshala.hashnode.dev/practical-guide-to-retrival-augmented-generation-from-scratch)

## What are the Business Problems & How RAGs can help (Make more money) 🎯
