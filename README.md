# Demo of Pydantic basics

## 1. Project setup using UV Package Manager
### 1.1. Installing uv :-

`curl -LsSf https://astral.sh/uv/install.sh | sh`

### 1.2. Checking version :-

`uv --version`

### 1.3. Installing python through uv and setting it as default :-

`uv python install 3.12 --default`

### 1.4. Listing Python versions available and installed :-

`uv python list`

### 1.5. Verifying Python Installation :-

`uv run python --version`

### 1.6. Setup basic project with .python-version, main.py, pyproject.toml, README.md:-

```
uv init demopydantic 
uv init demouv
```

## 2. Pydantic basics

Please refer the Jupyter notebook [intro.ipynb](https://github.com/naraharisrivatsa/demopydantic/blob/main/intro.ipynb) for a basic intro into Pydantic basics.

## Credits

Special thanks to [Krish Naik](https://www.udemy.com/user/krish-naik/) and the [Udemy course: Complete Agentic AI Bootcamp With LangGraph and Langchain](https://www.udemy.com/course/complete-agentic-ai-bootcamp-with-langgraph-and-langchain/) for providing valuable resources and guidance used in this project.
