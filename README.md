# Perplexity Spaces Prompt Collections

Reusable system prompts for Perplexity Spaces, organized as one folder per assistant.

## Quick Start

### Prerequisites
- A Perplexity account with access to Spaces
- Git (only needed if you want to clone/edit this repo)

### Clone
```bash
git clone https://github.com/akilesh/perplexity-spaces-prompts.git
cd perplexity-spaces-prompts
```

### Use a Space Prompt
1. Open a folder (for example `PromptTacular/`).
2. Copy the contents of `system_prompt.md`.
3. Paste it into your Perplexity Space system prompt.

## Core Capabilities
- Curated, ready-to-use system prompts for specific assistant workflows
- Folder-based structure that keeps each Space isolated and easy to version
- Clear per-space documentation (`README.md`) alongside each prompt

## Configuration
This repository has no required environment variables or runtime setup.

## Usage Example
```text
Use PromptTacular to rewrite, generate, or template prompts for LLM applications.
```

Current space:
- `PromptTacular/`: high-precision prompt rewriting, prompt generation, and developer-oriented prompt templates

## Contributing
```bash
git checkout -b codex/<short-change-name>
# edit prompt files and README content
git commit -am "<clear change summary>"
```

Contribution guidelines:
- Keep prompts explicit, testable, and scoped to one assistant goal.
- Update the relevant per-space `README.md` when behavior changes.
- Keep examples concise and directly runnable in chat products.

## License
MIT
