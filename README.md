# Ramsey van der Meer

I build AI systems that actually have to run in production: RAG apps, agentic workflows, evaluation tools, auth-heavy backend services, and the infrastructure around them.

Most of my recent work sits at the edge of AI and systems engineering. I like taking a rough model-powered idea and turning it into something observable, secure, and reliable enough for real users.

## What I Work On

- AI applications with LLMs, RAG, embeddings, vector search, and evaluation loops
- Backend systems in Python, FastAPI, Go, TypeScript, PostgreSQL, Redis, and Kafka
- Production infrastructure with GCP, Docker, Kubernetes, Terraform, GitHub Actions, Prometheus, and Grafana
- Agentic workflows, browser automation, data pipelines, and reliability tooling

## Featured Projects

### [MIST](https://github.com/RamseyvanderMeer/mist)

An AI-powered automotive diagnostics platform that turns fault codes, vehicle context, and technical repair content into repair guidance. Built with FastAPI, conversational RAG, ChromaDB, GCP Cloud Run, Google OAuth, Redis rate limits, and secure API access.

Demo: [mist-expo.vercel.app/sign-in](https://mist-expo.vercel.app/sign-in)

### [Autonomous X Research Agent](https://github.com/RamseyvanderMeer/social-media-inference-bot)

A Grok + LlamaIndex research agent over simulated X data. It plans, decomposes tasks, calls tools, retrieves context with hybrid semantic/keyword search, replans when results are weak, and exports evaluation metrics.

No hosted demo right now because it depends on model API keys, but the repo includes Docker setup, mock data generation, and evaluation outputs so the workflow can be run locally.

### [LLM Ranking by ELO](https://github.com/RamseyvanderMeer/rankingElo)

A lightweight human-preference ranking app for comparing LLM responses. It uses pairwise voting and ELO-style updates to turn subjective model outputs into a more useful ranking signal.

### [LLM Testing](https://github.com/RamseyvanderMeer/llm-testing)

An early evaluation pipeline for comparing LLM-generated data corrections across OpenAI, Anthropic, Gemini, Llama, and Mistral-style providers, with JSON repair and scoring workflows.

No hosted demo; this is mainly a reproducible evaluation/prototyping repo for comparing provider behavior and failure modes.

## Links

- Website: [ramseyvdm.com](https://www.ramseyvdm.com)
- LinkedIn: [linkedin.com/in/ramseyvandermeer](https://www.linkedin.com/in/ramseyvandermeer)
