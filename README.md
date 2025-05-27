# Configure

run docker compose up

download ollama

https://ollama.com/download/windows

download deepseek so n8n can understand model

ollama run deepseek-r1:1.5b

# n8n

http://localhost:5678/

add ollama chat model

http://ollama:11434/

![ollama](imgs/ollama.png)

![model](imgs/model.png)

## testing

![testing](imgs/testing.png)

# Using deepseek as a API

create HTTP request node

http://ollama:11434/api/chat

```json
{
  "model": "deepseek-r1:1.5b",
  "messages": [{ "role": "user", "content": "Solve: 25 * 25" }],
  "stream": false
}
```