# Hi, I'm Çağkan

I build LLM agents and RAG systems in Python.
I care about agents that are safe to run: code-based orchestration, least-privilege
tools, validated outputs and a human in the loop for decisions that matter.

## Projects

- **[Fixwright](https://github.com/ozcivitcagkan/Fixwright-Enterprise-AI-Reliability-Integration-Platform)** ([live demo](https://fixwright.onrender.com)):
  AI incident analysis for IT support teams, usable from a web app, a REST API and an MCP server.
  A LangGraph agent finds similar past incidents with pgvector (RAG), reuses only analyses
  a person approved, and returns a structured analysis that is saved only after a human
  approves it (interrupt() with a Postgres checkpointer). Measured with a retrieval eval and
  an agent eval (60/60 checks over 3 runs, code checks plus an LLM judge).
  React + TypeScript web app with a demo mode, FastAPI, tests with a fake model in CI,
  deployed with Docker on Render and Neon.
- **[AI Marketplace Listing Assistant](https://github.com/ozcivitcagkan/AI-Marketplace-Listing-Assistant)**:
  multi-agent assistant that drafts second-hand car listings from verified facts only.
  Deterministic workflow, per-agent tool permissions, claim-to-fact validation, safety
  review, two human approval gates, full test suite with a fake LLM client.
- **[AI Agent Patterns](https://github.com/ozcivitcagkan/ai-agent-patterns)**:
  step-by-step scripts for ReAct, memory, LangGraph, multi-agent supervisors, guardrails
  and RAG evaluation.
- **[Document Assistant](https://github.com/ozcivitcagkan/document_assistant)**:
  RAG command-line app for asking questions about your own PDF, TXT and DOCX files.

## Tools

Python · Anthropic API · LangGraph · MCP · FastAPI · PostgreSQL · pgvector · Pydantic · React · TypeScript · Docker · GitHub Actions · LangSmith · Voyage AI · ChromaDB · SQLite · SQL · Streamlit · pytest

## Contact

[LinkedIn](https://www.linkedin.com/in/cagkanozcivit)
