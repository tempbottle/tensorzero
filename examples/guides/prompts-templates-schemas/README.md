# Guide: Prompt Templates & Schemas

This directory contains the code for the **[Prompt Templates & Schemas](https://www.tensorzero.com/docs/gateway/guides/prompt-templates-schemas)** guide.

## Running the Example

1. Install the Python Dependencies:

```bash
# Using vanilla Python
pip install -r requirements.txt
```

or

```bash
# Using uv
uv venv && uv pip sync requirements.txt
```

2. Launch the TensorZero Gateway and ClickHouse database:

```bash
docker compose up
```

3. Run the example:

```bash
# Using vanilla Python
python run.py
```

or

```bash
# Using uv
uv run python run.py
```
