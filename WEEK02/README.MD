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

### Code for Assignment 1

📂 Repo: https://github.com/BCAPATHSHALA/RAGApplication

## Blogs

1. `Blog 1:` Write an article about Retrieval Augmented Generation (RAG) on Hashnode
2. `Blog + Research:` Where RAGs Fail? 🎯

### Links to Blogs

- [Retrieval Augmented Generation (RAG)](https://bcapathshala.hashnode.dev/practical-guide-to-retrival-augmented-generation-from-scratch)

## What are the Business Problems & How RAGs can help (Make more money) 🎯

You should research the business problems and take analysis of these given RAGs websites and make a list of the business problems and how RAGs can help.

1. https://sitegpt.ai
2. https://www.kapa.ai
3. https://notebooklm.google
4. https://www.chatpdf.com
5. https://www.chatpdf.com
6. https://askyourpdf.com

## Resources

- [LangChain RAG](https://js.langchain.com/docs/tutorials/rag/)
- [7 Practical Applications of RAG Models](https://hyperight.com/7-practical-applications-of-rag-models-and-their-impact-on-society/)
- [RAG with MCP](https://www.analyticsvidhya.com/blog/2025/06/rag-with-mcp/)
- [Building a Cost Efficient RAG Application](https://ambilio.com/building-a-cost-efficient-rag-application-a-guide-for-enterprises/)
- [Enhance Your RAG Applications with Knowledge Graph](https://www.singlestore.com/blog/enhance-your-rag-applications-with-knowledge-graph-rag/)
- [Tools for RAG Applications](https://www.analyticsvidhya.com/blog/2024/10/tools-for-rag-applications/)
- [A Practical Guide to Building Local RAG Applications with LangChain](https://machinelearningmastery.com/a-practical-guide-to-building-local-rag-applications-with-langchain/)

# GenAI Class 5 - Cohort 1

In this class, we will be learning about RAG Pipeline - System Design.

## Topics covered

System Design of RAGs (Production-Ready)

1. Basic RAG flow: query → retrieve → generate answer
2. Why improve RAG: accuracy, speed, cost, scalability issues in real use
3. Query rewriting / translation: make queries clearer for better search
4. CRAG (Corrective RAG): fix poor retrieval automatically
5. Ranking: order retrieved docs so best ones go to LLM
6. HyDE: generate a hypothetical answer first, then use it to find real docs

## Assignments (Optional)

1. `Assignment 1:` Build a production ready RAG application 🎯

## Blogs

1. `Blog 1:` [System Design of RAGs Pipeline?](https://bcapathshala.hashnode.dev/system-design-of-rags-pipeline)

## Resources

- https://arxiv.org/html/2401.05856v1
- https://www.merge.dev/blog/rag-challenges
- https://digitaloneagency.com.au/best-vector-database-for-rag-in-2025-pinecone-vs-weaviate-vs-qdrant-vs-milvus-vs-chroma
- https://arxiv.org/html/2405.07437v2
- https://aws.amazon.com/blogs/machine-learning/detect-hallucinations-for-rag-based-systems
- https://www.pinecone.io/learn/retrieval-augmented-generation/?utm_source=chatgpt.com
- https://zerogravitymarketing.com/blog/the-science-behind-rag
- https://www.mindee.com/blog/rag-hallucinations-explained
- https://www.scoutos.com/blog/how-to-reduce-ai-hallucinations-with-rag
- https://machinelearningmastery.com/understanding-rag-part-viii-mitigating-hallucinations-in-rag
- https://www.gsdvs.com/post/how-retrieval-augmented-generation-can-reduce-hallucinations
- https://arxiv.org/abs/2404.08189
- https://coralogix.com/ai-blog/rags-are-not-the-solution-for-ai-hallucinations
- https://blog.curiosity.ai/%EF%B8%8F-why-your-rag-system-is-failing-and-how-to-fix-it-7fe66780a335
- https://www.marktechpost.com/2024/08/18/the-challenges-of-implementing-retrieval-augmented-generation-rag-in-production
- https://cloud.google.com/blog/products/ai-machine-learning/optimizing-rag-retrieval
- https://www.patronus.ai/llm-testing/rag-evaluation-metrics
- https://xenoss.io/blog/vector-database-comparison-pinecone-qdrant-weaviate
- https://cloud.google.com/blog/products/ai-machine-learning/optimizing-rag-retrieval
- https://www.ibm.com/think/insights/rag-problems-five-ways-to-fix

# GenAI Class 6 - Cohort 1

In this class, we will be learning about introduction to LangGraph.

## Topics covered

1. What is LangGraph?
2. Why LangGraph is used?
3. How LangGraph works?
4. What is Agentic SDK?
5. Why Agentic SDK is used?
6. How Agentic SDK works?
7. What is the difference between LangGraph and Agentic SDK?
8. Which one to use from LangGraph and Agentic SDK?
9. OpenAI Agentic SDK, OpenAI Function Tool, & Vercel AI Agentic SDK
10. What are autonomous and procesures flows?
11. What is LangSmith and OpenAI Agentic Tracing?

## Assignments (Optional)

1. `Assignment 1:` Use LangGraph to build a AI Agent 🎯

## Blogs (Optional)

1. `Blog 1:` Write an article about each topic that you have covered in this class 🎯

## Resources

1. https://ai-sdk.dev
2. https://platform.openai.com/docs/guides/function-calling
3. https://openai.github.io/openai-agents-python/tracing/
4. https://community.openai.com
