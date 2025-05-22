# API Debugging Assistant

## Project Description

This project implements a **multi-modal, tool-augmented, agent-based conversational AI assistant** designed to help developers diagnose, understand, and resolve issues while working with APIs.

Whether it's authentication failures, unexpected responses, invalid payloads, or endpoint confusion, the assistant can parse logs or screenshots, retrieve relevant documentation, simulate requests, and deliver clear, actionable solutions—powered by large language models and integrated tools.

The assistant uses a **workflow graph** architecture built with [LangGraph](https://github.com/langchain-ai/langgraph), and integrates external APIs, LLM function calling, and real-time diagnostics through modular [LangChain](https://docs.langchain.com/docs/tools/) tools.

## Key Capabilities

* Understands and processes error logs and screenshots (via OCR)
* Retrieves relevant API documentation from a vector database
* Simulates endpoint calls to validate parameters and API keys
* Uses LLM tools and functions to explain and fix errors
* Maintains conversation history and user context
* Chains reasoning using LangGraph’s DAG-based workflows
* Produces natural, clear, multi-step responses with suggested fixes

