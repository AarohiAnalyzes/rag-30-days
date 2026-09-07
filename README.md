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

## Day 03: Mini RAG System

### What I Plan to Build

Build a simple **end-to-end Mini RAG System** from scratch using everything learned so far.

The system will:

* Store a small document collection
* Generate document embeddings
* Convert user questions into embeddings
* Retrieve relevant documents
* Build context automatically
* Send context + question to Gemini
* Generate the final answer
* Organize the pipeline into reusable Python functions

### Goal

Move from manually executing individual RAG steps to a reusable function such as:

```python
answer_question("What is RAG?")
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
* [ ] Day 03 — Mini RAG System
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

The goal is to understand **what happens inside a RAG system**, first building the components from scratch and later introducing frameworks and more advanced techniques.
