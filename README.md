# LangChain for LLM Application Development

This repository contains my notebooks and hands-on implementations from the **[LangChain for LLM Application Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)** short course by **DeepLearning.AI**, taught by Andrew Ng and Harrison Chase (creator of LangChain).

The course covers the core building blocks of the [LangChain](https://www.langchain.com/) framework for building applications powered by large language models (LLMs), and this repo documents my implementation of each module.

## What's Inside

| Notebook | Topic |
|---|---|
| `MODEL_PROMPT_PARSER_CODE.ipynb` | **Models, Prompts & Parsers** — Working with LLM APIs directly, building reusable prompt templates with `ChatPromptTemplate`, and parsing LLM outputs into structured formats using `ResponseSchema` and `StructuredOutputParser`. |
| `MEMORY.ipynb` | **Memory** — Giving conversational chains context/state using `ConversationBufferMemory`, `ConversationBufferWindowMemory`, `ConversationTokenBufferMemory`, and `ConversationSummaryBufferMemory`. |
| `QUESTIONS_AND_ANSWERS_RAG.ipynb` | **Q&A over Documents (RAG)** — Building a retrieval-augmented generation pipeline over a custom CSV dataset using `CSVLoader`, `OpenAIEmbeddings`, `DocArrayInMemorySearch`, and `RetrievalQA`. |
| `EVALUATION.ipynb` | **Evaluation** — Generating QA test cases automatically with `QAGenerateChain` and evaluating chain outputs with `QAEvalChain`, including debugging chain execution with `langchain.debug`. |
| `AGENTS.ipynb` | **Agents** — Building LLM agents that can use tools (Wikipedia search, a Python REPL tool, and custom `@tool`-decorated functions) via `initialize_agent` and `AgentType`. |

## Real-World Benefits — What Can You Build With This?

The patterns in these notebooks aren't just course exercises — each one maps directly to a real, usable application:

- **Models, Prompts & Parsers** → Turn messy, unstructured LLM text into clean structured data (JSON, dictionaries). Useful for things like extracting sentiment, gift-worthiness, or delivery days from customer reviews automatically — no manual regex or string parsing needed.
- **Memory** → Build chatbots and assistants that actually remember context across a conversation, instead of treating every message as a fresh, isolated request. Essential for any customer-support bot, tutoring bot, or personal assistant.
- **Q&A over Documents (RAG)** → Ask natural-language questions over your *own* data (CSVs, PDFs, internal docs) instead of relying only on what the LLM was trained on. This is the core pattern behind internal knowledge-base bots, document search tools, and "chat with your data" apps.
- **Evaluation** → Automatically generate test questions and grade an LLM pipeline's answers, instead of manually checking outputs one by one. Critical for catching regressions before shipping an LLM-powered feature.
- **Agents** → Let an LLM decide *which tool to use* (search, code execution, custom functions) to solve a task, rather than hardcoding the logic yourself. This is the foundation for building autonomous assistants that can look things up, run calculations, and take multi-step actions.

Together, these five notebooks form a practical toolkit for building production-style LLM applications — from structured data extraction to a fully agentic, memory-aware, document-grounded assistant.

## Tech Stack

- **Python**
- **LangChain**
- **OpenAI API** (`gpt-3.5-turbo`)
- **DocArray** (in-memory vector store for RAG)
- **Jupyter Notebook**

## Course Reference

- Course: [LangChain for LLM Application Development](https://www.deeplearning.ai/courses/langchain?_gl=1*ndx9b9*_gcl_au*MTkwMjMxMDk5MS4xNzg1ODM1NzUx*_ga*MTcwOTQ0MDgyNi4xNzg1ODM1NzUw*_ga_FR2MZ1VLMS*czE3ODg1MjIyMzMkbzM2JGcxJHQxNzg4NTIyMjcwJGoyMyRsMCRoMA..) by DeepLearning.AI
- Instructors: Andrew Ng, Harrison Chase

## About Me

**Aakar Sonawane**
Final-year B.Tech CSE (AI/ML) student, building a career in AI/ML engineering.
[GitHub](https://github.com/aakar-sonawane) · [LinkedIn](https://linkedin.com/in/aakar-sonawane-60a3b838b)
