# Personalized RAG Chatbot

## Problem Statement
To build a personalized RAG system with a chatbot for a financial assistant. The architecture must maintain a dedicated context layer that injects user-specific data into retrieval, prompt construction, and agent behavior while keeping enterprise knowledge grounding separate from profile data.

## Solution Design
- Agentic Flow: an agentic chatbot that retrieves relevant financial knowledge and adapts its communication style to each user's profile
- Orchestration: the system combines Retrieval-Augmented Generation with user memory, profile-driven persona selection, and safety guardrails to deliver contextually grounded, personalized financial guidance.

## Tech Stack
- LLM & Orchestration: RAG (Retrieval-Augmented Generation), LangGraph
- Prompt Engineering: DSPy, LangChain
- Chat history management: Mem0
- Evaluation: RAGAS (Proposed)

## Future Applicability
- Scalable architecture for personalized RAG systems across various domains beyond finance
- Framework for integrating complex information sources, user profiles, historical interactions, and safety mechanisms in agentic applications.

## Relevant AI Use Case Category
<table style="border:1px solid gray; border-collapse: collapse;">
  <tr>
    <th style="border:1px solid gray;">Information Search</th>
    <th style="border:1px solid gray;">AI Augmented Product</th>
    <th style="border:1px solid gray;">AI Coworker</th>
  </tr>
  <tr>
    <td style="border:1px solid gray; text-align: center;">✓</td>
    <td style="border:1px solid gray; text-align: center;">✓</td>
    <td style="border:1px solid gray; text-align: center;">✓</td>
  </tr>
</table>

## Github Repository
- [Personalized RAG Chatbot](https://github.com/Alexxbyou/personalized-rag-agentic)
