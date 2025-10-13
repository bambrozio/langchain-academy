

* Install `uv`:
```shell
brew install uv
```

* Create the Python virtual env:
```shell
uv venv --python 3.11
```

* Install Python libraries:
```shell
pip install -r requirements.txt
```

* Create a `.env` file:
```.env
LANGSMITH_API_KEY=...
LANGSMITH_TRACING_V2=true
LANGSMITH_PROJECT=langchain-academy
# OPENAI_API_KEY=.... (I will use LM Studio locally instead)
TAVILY_API_KEY=...
```

