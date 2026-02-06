\# Lumina-Chat-Workbench 🌐🤖

\*\*A Unified Multi-Model Interface for LLM Comparison and Local Deployment\*\*



\##  Overview

Lumina-Chat is a model-agnostic workbench designed for real-time comparison between industry-leading LLMs and local open-source models. It provides a standardized interface to evaluate performance, latency, and reasoning across \*\*OpenAI, Anthropic, Google Gemini, and Ollama (Local)\*\*.



\##  Key Features

\- \*\*Provider Agnostic\*\*: Switch between GPT-4o, Claude 3.5, and Gemini 1.5 Pro within a single session.

\- \*\*Local Model Support\*\*: Deep integration with \*\*Ollama\*\*, allowing private, on-premise inference.

\- \*\*Performance Benchmarking\*\*: Side-by-side comparison of response times and token generation efficiency.

\- \*\*Dynamic Configuration\*\*: Per-model settings for temperature, top-p, and system prompts.

\- \*\*Edge Deployment\*\*: Optimized for Vercel Edge functions for ultra-low latency API routing.



\##  Tech Stack

\- \*\*Frontend\*\*: React 18, TypeScript, Vite, Tailwind CSS.

\- \*\*Backend\*\*: Node.js / TypeScript (Edge-compatible).

\- \*\*Integrations\*\*: OpenAI SDK, Anthropic SDK, Google AI SDK, Ollama API.

\- \*\*UI Components\*\*: Shadcn UI / Custom Headless Components.



\##  Architecture

\- `/web/src/services/api.ts`: Unified abstraction layer for multi-provider API calls.

\- `/web/src/hooks/useChat.ts`: Custom React hook managing multi-turn conversation state.

\- `/server/api/chat.ts`: Serverless route handler for secure API key proxying.



---

\*Developed to facilitate LLM benchmarking and local model experimentation.\*

