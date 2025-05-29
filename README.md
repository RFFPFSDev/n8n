# Configure

## 1 - Run docker compose up

pull deepseek so n8n can understand model

## 2 - ollama pull deepseek-r1

![pulldeepseek](imgs/pulldeepseek.png)

Now, you should be able to see the model in docker volume

![volumedeepseek](imgs/volumedeepseek.png)

# n8n

http://localhost:5678/

If you did step 2 (pull deepseek-r1), n8n should be contain deepseek-r1 in the list of models

add ollama chat model

http://ollama:11434/

![ollama](imgs/ollama.png)

![model](imgs/model.png)

## testing

![testing](imgs/testing.png)

## Reference:

https://github.com/n8n-io/self-hosted-ai-starter-kit