# AI Learning Course Notes

This README is a running set of notes for learning AI. More topics and setup steps can be added over time.

## Python Setup

### Install Python

Installs Python 3.12 on macOS using Homebrew so you have the correct Python version for local development.

```bash
brew install python@3.12
```

### Verify Installation

Checks that Python 3.12 was installed correctly and shows the installed version.

```bash
python3.12 --version
```

## Virtual Environment Setup

### Create a Virtual Environment (Mac)

Creates an isolated Python environment named `venv` so project packages do not affect your global Python setup.

```bash
python3.12 -m venv venv
```

### Activate the Virtual Environment

Turns on the virtual environment so any packages you install go inside this project instead of system-wide.

```bash
source venv/bin/activate
```

## Install Packages

Installs the `openai` package to work with OpenAI APIs and `langchain` to build AI workflows and chains.

```bash
pip install openai langchain
```


To run python use python3 <filename> 
```bash
python3 app.py
```
## Notes To Add Later

- API keys and environment variables
- First OpenAI script
- LangChain basics
- Project exercises
