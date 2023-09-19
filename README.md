
<div style="text-align:center">
<h1>
Deep Page Sales Rep <br>
</h1>
Sophisticated LLM Prompt for Chatbot
</div>

## What did we do here?
- [x] LangChain Prompt
- [x] Chatbot
- [x] ChatGPT-style UI (React.js)
- [ ] Django Backend
 
<img width="360px" alt="image" src="https://user-images.githubusercontent.com/98614666/232768610-fdeada85-3d21-4cf9-915e-a0ec9f3b7a9f.png">

## Install the required dependencies by running the following command:

```
pip install -r requirements.txt
```

### Configure the Application
To configure the application, there are a few properties that can be set either via the environment or via config.json.  The environment variable takes priority.

| Field               | Env Variable    | config.json     | examples                                           |
|---------------------|-----------------|-----------------|----------------------------------------------------|
| The OpenAI Api Key  | OPENAI_API_KEY  | openai_key      | sk-...                                             
| The OpenAI Base URL | OPENAI_API_BASE | openai_api_base | https://api.openai.com <br> http://my-reverse-proxy/ 

Use the Base URL if you need to run your queries through a reverse proxy (like [this one](https://github.com/stulzq/azure-openai-proxy) which will run your queries through Azure's OpenAI endpoints )

### Running the Application
To run the application, make sure the virtual environment is active and run the following command:
```
python run.py
```

### Docker
The easiest way to run ChatGPT Clone is by using docker
```
docker-compose up
```
