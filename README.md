# Calling Bedrock Models with LangChain

Demonstrates how to build AI applications by calling Amazon Bedrock foundation models through LangChain. Includes a working staff scheduling chatbot that accepts natural language requests and routes them to the appropriate Bedrock model.

**Portfolio write-up:** [Calling Bedrock Models with LangChain](https://viet-in-tech.github.io/langchain-bedrock-models.html)

---

## What's in This Repo

| File | Description |
|------|-------------|
| `bedrock_langchain_demo.ipynb` | Notebook walking through Bedrock model invocation with LangChain |

## Overview

This project covers the practical workflow for connecting LangChain to Amazon Bedrock-hosted models — setting up AWS credentials, selecting a model (Claude, Titan, etc.), and wrapping the invocation in LangChain's abstraction layer.

The chatbot example shows how to pass user messages through a LangChain chain backed by a Bedrock model to generate structured responses — a reusable pattern for any LangChain-powered AI application on AWS.

## Key Concepts

- Configuring `ChatBedrock` as a LangChain LLM backend
- Building prompt templates and chains with LangChain Expression Language (LCEL)
- Comparing synchronous vs. streaming invocation
- Practical patterns for staff scheduling and other structured reasoning tasks

## Tech Stack

- Python
- LangChain · LangChain Expression Language (LCEL)
- Amazon Bedrock (Claude / Titan)
- AWS SDK (boto3)
- Jupyter Notebook
