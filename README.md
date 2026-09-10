# 30 Days of RAG Engineering

A hands-on 30-day journey to learn and build Retrieval-Augmented Generation (RAG) systems from scratch, progressing from embeddings and semantic search to advanced RAG concepts.

---

## Day 01: Embeddings & Semantic Search

### What I Learned

* What embeddings are
* Converting text into vectors
* Cosine similarity
* Semantic search
* Top-K retrieval
* Similarity thresholds
* Ranking documents based on semantic similarity

### Project

Built a **mini semantic search engine** using Sentence Transformers, NumPy, and cosine similarity to retrieve the most relevant documents for a given query.

---

## Day 02: Basic RAG

### What I Learned

* What RAG (Retrieval-Augmented Generation) is
* How retrieval and generation work together
* Creating query embeddings
* Retrieving relevant documents
* Building context from retrieved documents
* Passing context to an LLM
* Generating answers using Gemini
* Difference between answering with and without retrieved context

### Project

Built a **basic RAG pipeline from scratch** using Sentence Transformers for retrieval and Gemini for generation.

### RAG Pipeline

```text
User Question
      ↓
Query Embedding
      ↓
Similarity Search
      ↓
Top-K Retrieval
      ↓
Context
      ↓
Gemini LLM
      ↓
Generated Answer
```

---

## Day 03: Mini RAG Pipeline

### What I Learned

* Building a small RAG system from individual components
* Creating document embeddings for a knowledge base
* Converting a user question into an embedding
* Calculating cosine similarity between the query and documents
* Finding the most relevant document
* Retrieving the Top-K relevant documents
* Understanding document ranking using `np.argsort()`
* Building a context from retrieved documents
* Passing retrieved context and the question to Gemini
* Generating an answer grounded in the retrieved context

### Project

Built a **Mini RAG Pipeline from scratch** using a small knowledge base containing documents about Python, Machine Learning, RAG, Docker, APIs, Redis, RabbitMQ, and Vector Databases.

The pipeline retrieves the most relevant documents for a question and provides them as context to Gemini before generating the final answer.

### Example

**Question:**

```text
What is RAG?
```

**Retrieved Context:**

```text
Retrieval-Augmented Generation, or RAG, combines information
retrieval with language generation to provide an LLM with
relevant external context.
```

**Generated Answer:**

```text
Based on the provided context, RAG stands for
Retrieval-Augmented Generation. It combines information
retrieval with language generation to provide a large
language model (LLM) with relevant external context.
```

### Day 03 Pipeline

```text
User Question
      ↓
Query Embedding
      ↓
Cosine Similarity
      ↓
Document Ranking
      ↓
Top-K Retrieval
      ↓
Context Creation
      ↓
Gemini LLM
      ↓
Final Answer
```

---

## Tech Stack

* Python
* Google Colab
* NumPy
* Sentence Transformers
* Scikit-learn
* Gemini API
* Google GenAI SDK

---

## Progress

* [x] Day 01 — Embeddings & Semantic Search
* [x] Day 02 — Basic RAG
* [x] Day 03 — Mini RAG Pipeline
* [ ] Day 04
* [ ] Day 05
* [ ] Day 06
* [ ] Day 07
* [ ] Day 08
* [ ] Day 09
* [ ] Day 10
* [ ] Day 11
* [ ] Day 12
* [ ] Day 13
* [ ] Day 14
* [ ] Day 15
* [ ] Day 16
* [ ] Day 17
* [ ] Day 18
* [ ] Day 19
* [ ] Day 20
* [ ] Day 21
* [ ] Day 22
* [ ] Day 23
* [ ] Day 24
* [ ] Day 25
* [ ] Day 26
* [ ] Day 27
* [ ] Day 28
* [ ] Day 29
* [ ] Day 30

---

## Learning Approach

Each day focuses on building something small and practical rather than only learning theory.

The goal is to understand **what happens inside a RAG system** by first building the core components from scratch and gradually moving toward more advanced RAG techniques, tools, frameworks, and production-oriented concepts.
