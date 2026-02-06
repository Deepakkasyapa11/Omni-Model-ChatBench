# Local Model Integration Guide (Ollama)

This workbench supports local inference via Ollama to ensure data privacy and cost-efficiency.

## Prerequisites
1. Install Ollama from [ollama.com](https://ollama.com).
2. Pull your desired model: `ollama pull llama3` or `ollama pull mistral`.

## Connecting to Lumina-Chat
1. Ensure Ollama is running on `http://localhost:11434`.
2. In the Lumina Settings, set the Base URL to your local Ollama endpoint.
3. Select 'Local Model' from the provider dropdown.

## Troubleshooting
- If connection fails, check CORS settings for Ollama by setting the environment variable `OLLAMA_ORIGINS="*"` on your host machine.
