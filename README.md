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

Use prompt flow to test chat app

```cli
pf flow test --flow ./copilot_flow --inputs chat_input="how much do the Trailwalker shoes cost?"
```

Run the interactive UI

```cli
pf flow test --flow ./copilot_flow --ui
```

Test with chat history

```cli
pf flow test --flow ./copilot_flow --inputs ./copilot_flow/input_with_chat_history.json
```

Evaluation

```cli
python evaluate.py
```