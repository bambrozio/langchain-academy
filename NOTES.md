# LangChain Academy’s Introduction to LangGraph course
* https://academy.langchain.com/courses/take/intro-to-langgraph/texts/58238105-getting-set-up

## Notes
1. This branch contains a fork of https://github.com/langchain-ai/langchain-academy refactored to use https://lmstudio.ai/ and https://docs.astral.sh/uv/.
2. LM Studio and UV integration borrowed from https://github.com/guozheng/hello-langgraph.

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
uv init --bare
pip install -r requirements.txt
uv add -r requirements.txt
```

* Create a `.env` file:
```.env
LANGSMITH_API_KEY=...
LANGSMITH_TRACING_V2=true
LANGSMITH_PROJECT=langchain-academy
# OPENAI_API_KEY=.... (I will use LM Studio locally instead)
TAVILY_API_KEY=...

LMSTUDIO_BASE_URL=http://localhost:1234/v1
LMSTUDIO_MODEL=qwen3-32b
LMSTUDIO_API_KEY=lm-studio
```

