## Quick Start for Creating a Vector Database for LLM with RAG

I'm working to learn more about how I can use large language models (LLM) with retrieval-augmented generation (RAG) to improve existing process and work-pipelines by offloading repetitive tasks. A part of expanding my knowledge around LLMs and RAG includes being able to generate a body of knowledge that is specific to the process or work-pipeline that I'm targeting at the time.

To help me focus on getting to a RAG and not be swallowed by the vast amount of information on the topic or the other options like knowledge graphs, I've decided to begin my exploration using Chroma (Chroma). Chroma is an open-source (Apache 2.0) vector database that, from what I can tell, provides a simple Python SDK and CLI that I can use to build out my knowledge base.

## Prerequisities

1. Python 3.13.2 or later
2. ChromaDB 1.0.15 or later
3. IPYKernel 6.29.5 or later
4. Poetry

## Development

### Virtual Environment via `pyenv`
The project

0. Install the required version of Python for this project, currently at `>=3.13`.

1. Create a new virtual environment for this project using `pyenv`

```
pyenv virtualenv <PYTHON_VERSION> audit_webpage_metadata
```

2. Activate the virtual environment

```
pyenv activate audit_webpage_metadata
```


### Install Dependencies via `poetry`
The project is managed using Poetry, a Python packaging and depdency manager. More information can be found on the [official Poetry project website](https://python-poetry.org/).

1. Install the package with dependencies

```
poetry install --no-root
```
