# LLM Pentester Playground

This is a docker compose using ollama, open-webui and a custom pipeline filter implementing a LLM firewall. It was designed to train your skills in Prompt Injection and LLM security.

WARNING! This tool is for education purposes and training, but **it has not been designed to be secure**. Please avoid using it in production or exposed environments.

## Usage

1. Start docker compose

```sh
docker compose up
```

2. Browse: http://127.0.0.1:8080
3. User -> Settings -> Admin Settings -> Models: Download your favourite model (for example `llama3.2:3b`).
4. User -> Settings -> System Prompt: Include your prompt with secrets there.
5. User -> Settings -> Admin Settings -> Pipelines: Configure your LLM Firewall.
