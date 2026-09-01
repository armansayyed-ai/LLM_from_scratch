# LLM from Scratch

Building Large Language Models (LLMs) from scratch - exploring the fundamentals and architecture of language models.

## Project Overview

This project focuses on understanding and implementing the core concepts behind Large Language Models, including:
- Transformer architecture
- Attention mechanisms
- Training strategies
- Fine-tuning approaches

## Getting Started

### Prerequisites
- Python 3.10+
- [uv](https://docs.astral.sh/uv/) (`powershell -c "irm https://astral.sh/uv/install.ps1 | iex"` on Windows)

### Installation

```powershell
git clone https://github.com/armansayyed-ai/LLM_from_scratch.git
cd LLM_from_scratch
uv venv .venv --python 3.12
.\.venv\Scripts\Activate.ps1
uv pip install -r requirements.txt
```

macOS/Linux: `source .venv/bin/activate` instead of the Activate.ps1 line.

For CUDA PyTorch, follow the install command on [pytorch.org](https://pytorch.org) after the requirements install.

In the notebook kernel picker, select **`.venv (Python 3.12)`**. That is this project's virtual environment.

## Project Structure

```
LLM_from_scratch/
├── data/              # Datasets (gitignored except placeholders)
├── models/            # Model implementations
├── notebooks/         # Jupyter notebooks for exploration
├── src/               # Source code
├── tests/             # Unit tests
├── .env.example       # Environment variable template
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Arman Sayyed** - [GitHub Profile](https://github.com/armansayyed-ai)
