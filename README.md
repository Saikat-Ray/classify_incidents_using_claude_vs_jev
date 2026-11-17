# Incident Classification with Claude and Jev

This project compares two notebook-based approaches to classifying support
tickets into categories such as billing disputes, payment failures, technical
errors, account access issues, and feature requests.

## Notebooks

- `classify_using_claude.ipynb` classifies tickets with the Anthropic Claude API.
- `classify_using_jev.ipynb` classifies tickets with the TypeSafe System One API
  using the `jev-latest` model.

## Setup

Use Python 3.11 and activate the project virtual environment:

```bash
source .venv/bin/activate
```

Install the dependencies required by the notebooks and configure the API keys
in the root `.env` file:

```dotenv
ANTHROPIC_API_KEY=your_anthropic_api_key
TYPESAFE_API_KEY=your_typesafe_api_key
```

