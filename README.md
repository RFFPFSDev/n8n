# Configure

run docker compose up


pull deepseek so n8n can understand model

ollama pull deepseek-r1

![pulldeepseek](imgs/pulldeepseek.png)

See the model is in volume

![volumedeepseek](imgs/volumedeepseek.png)

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

## Reference:

https://github.com/n8n-io/self-hosted-ai-starter-kit