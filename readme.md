just testing some open models

## references

- https://dev.to/berk/running-ollama-and-open-webui-self-hosted-4ih5
- https://docs.openwebui.com/getting-started/quick-start/
- https://ollama.com/blog/ollama-is-now-available-as-an-official-docker-image

## models

Can explore more models here https://ollama.com/search

- deepseek-coder-v2:16b
- qwen2.5-coder:14b
- phi3:14b

```bash
# pull model using ollama hub
docker compose exec -it ollama ollama pull llama3.2
docker compose exec -it ollama ollama pull qwen2.5-coder:14b
docker compose exec -it ollama ollama pull phi3:14b
```
