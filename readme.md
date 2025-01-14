```markdown
# Langflow

Langflow is an open-source, Python-powered visual framework for building multi-agent and Retrieval-Augmented Generation (RAG) applications. With its intuitive drag-and-drop interface, Langflow simplifies the process of creating AI workflows, enabling developers to turn their ideas into functional solutions effortlessly.

## Features
- **Visual Flow Builder**: Create AI workflows without extensive coding using an intuitive drag-and-drop interface.
- **Customizable and Flexible**: Fully customizable, LLM and vector store agnostic, suitable for various use cases.
- **Powerful AI Tools**: Easily integrate prompts, language models, and data sources to build sophisticated applications.

## Use Cases
- Craft intelligent chatbots
- Build document analysis systems
- Generate compelling content
- Orchestrate multi-agent applications

## Community and Support
Join our vibrant community of developers and AI enthusiasts:
- [Contribute to Langflow](https://github.com/langflow/langflow)
- [Langflow Discord Server](https://discord.gg/langflow)
- Follow us on Twitter: [@langflow_ai](https://twitter.com/langflow_ai)

---

## Installation

Langflow can be installed locally or used as a hosted service with [DataStax Langflow](https://www.datastax.com).

### Prerequisites
- Python 3.10 to 3.12
- `uv`, `pip`, or `pipx` installed
- A virtual environment is recommended for isolating dependencies.

### Install Langflow Locally

#### Using `uv` (Recommended)
```bash
uv pip install langflow
```

#### Using `pip`
```bash
python -m pip install langflow
```

#### Using `pipx`
```bash
pipx install langflow --python python3.10
```

---

## Running Langflow

### Start Langflow
#### Using `uv`
```bash
uv run langflow run
```

#### Using `pip`
```bash
python -m langflow run
```

Visit [http://127.0.0.1:7860](http://127.0.0.1:7860) in a Chromium-based browser to confirm that Langflow is running.

---

## Managing Versions

### Upgrade Langflow
#### Using `uv`
```bash
uv pip install langflow -U
```

#### Using `pip`
```bash
python -m pip install langflow -U
```

### Install a Specific Version
```bash
python -m pip install langflow==<version>
```

### Force Reinstall
```bash
python -m pip install langflow --force-reinstall
```

---

## Hosted Solution: DataStax Langflow
DataStax Langflow is a hosted version integrated with Astra DB. It eliminates setup and installation, allowing you to get started in minutes. [Sign up for free](https://www.datastax.com).

---

## Troubleshooting

### Common Issues and Solutions

#### `No module named 'langflow.__main__'`
- Run with: `python -m langflow run`
- If unresolved:
  ```bash
  python -m pip install langflow -U
  python -m pip install langflow --force-reinstall
  ```

#### Migration Errors
- Clear the cache:
  - **Linux/WSL2**: `~/.cache/langflow/`
  - **MacOS**: `~/Library/Caches/langflow/`
- Backup files before clearing if needed.

#### Dependency Resolution Freezes
- Use `uv` instead of `pip`:
  ```bash
  uv pip install langflow
  uv run langflow run
  ```

For further assistance, join the [Langflow Discord Server](https://discord.gg/langflow).

---

Start building with Langflow and unleash the power of AI in your applications!
```