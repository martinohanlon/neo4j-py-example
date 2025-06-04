# Neo4j Python Examples

This repository contains code examples to use Python with Neo4j Aura.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new/martinohanlon/neo4j-py-example){:target="_blank"}

## Install

Install the [`neo4j` Python pakage](https://neo4j.com/docs/python-manual/current/).

```bash
pip install neo4j
```

## Examples

- [`examples/connect.py`](examples/connect.py)
- [`examples/transactions.py`](examples/transactions.py)

## Run

To run the examples, you will need to add your Neo4j environment details:

1. Install the [`python-dotenv` Python package](https://pypi.org/project/python-dotenv/):
    ```bash
    pip install python-dotenv
    ```
2. Create a new [`.env`](.env) file and copy the contents of the [`.env.example`](.env.example) file into it
3. Update the environment values in the [`.env`](.env) file with the values in your Aura Credentials file which you downloaded when creating your instance.
4. Run the [`test_environment.py`](./llm-knowledge-graph/test_environment.py) program to check the environment is set up correctly.

Install the [`python-dotenv` Python package](https://pypi.org/project/python-dotenv/)
