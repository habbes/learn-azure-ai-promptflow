# Azure OpenAI Prompt Flow chatbot

Based on the tutorial: [Build a custom chat app with the promot flow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/copilot-sdk-create-resources).

## Basic Dev instructions

Activate the environment

```cli
.venv/scripts/activate
```

Upgrade pip

```cli
pip -m pip install --upgrade pip
```

Install dependencies

```cli
pip install -r requirements.txt
```

Update dependencies file

```cli
pip freeze > requirements.txt
```

Deactivate environment

```cli
deactivate
```

## Commands

Build index

```cli
python build_index.py
```