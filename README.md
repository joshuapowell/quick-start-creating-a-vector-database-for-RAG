## Quick Start for Creating a Vector Database for LLM with RAG

I'm working to learn more about how I can use large language models (LLM) with retrieval-augmented generation (RAG) to improve existing process and work-pipelines by offloading repetitive tasks. A part of expanding my knowledge around LLMs and RAG includes being able to generate a body of knowledge that is specific to the process or work-pipeline that I'm targeting at the time.

To help me focus on getting to a RAG and not be swallowed by the vast amount of information on the topic or the other options like knowledge graphs, I've decided to begin my exploration using Chroma (Chroma). Chroma is an open-source (Apache 2.0) vector database that, from what I can tell, provides a simple Python SDK and CLI that I can use to build out my knowledge base.

## Prerequisities

1. Python 3.13.2 or later
2. ChromaDB 1.0.15 or later
3. IPYKernel 6.29.5 or later
4. Poetry

## Using

Launch one of the notebooks in the `notebooks` directory in your preferred Jupyter Notebook environment.

1. Explore how to use a vector database: [`exploring-chromadb.ipynb`](./notebooks/exploring-chromadb.ipynb)
2. Explore how to ETL PDF data into a vector database: [`exploring-data-extraction-from-pdf.ipynb`](./notebooks/exploring-data-extraction-from-pdf.ipynb)

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

## Disclaimer
The content, including but not limited to code, text, images, audio, and/or video, hereafter referred to as "content", in this document are provided for informational and educational purposes only. TO THE EXTENT PERMITTED BY APPLICABLE LAW, THE AUTHOR PROVIDES THIS DOCUMENT "AS IS" WITHOUT WARRANTY OF ANY KIND, INCLUDING WITHOUT LIMITATION, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NONINFRINGEMENT. In no event shall the author or their employer be liable for any claim, damages or other liability, direct or indirect, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the code and content or the use or other dealings in the code and content. Use this code and all other content at your own risk. 

**Third-party API Disclaimer:** Additionally, the code examples in this post may interact with third-party APIs and services. The availability and functionality of these APIs are subject to change without notice. The author is not responsible for any issues arising from changes to these APIs or any downtime or limitations imposed by the service providers. You are responsible for complying with the terms of service and usage policies of any third-party APIs you use in conjunction with this code. Use this code at your own risk, and be aware of potential security implications when connecting to external services.

**Product Link Disclaimer:** This blog post may contain links to products or services available for purchase. These links are provided to offer readers additional information and resources. The author's opinions expressed in this post are independent and not influenced by any potential commercial relationships. No compensation is received for including these links, and their presence does not constitute an endorsement. Readers are encouraged to conduct their own research before making any purchasing decisions.

## Copyright
Copyright &copy; 2025 J.I. Powell. All rights reserved.
