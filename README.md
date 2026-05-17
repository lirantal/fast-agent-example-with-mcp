# Fast Agent example

## Install

```bash
uv venv
source .venv/bin/activate
uv pip install fast-agent-mcp
```

## Configure

Copy the `example.fastagent.secrets.yaml` file to `fastagent.secrets.yaml` and fill in the required fields for setting an API key to one of the supported LLM providers.

## Run

Run the agent:

```
cd state-transfer
uv run agent_one.py
```


## Contributing

Please consult [CONTRIBUTING](./CONTRIBUTING.md) for guidelines on contributing to this project.
