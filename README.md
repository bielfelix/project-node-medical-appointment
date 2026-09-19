# LangGraph Prompt Chaining Reference Implementation

A technical implementation for building multi-step LLM workflows with LangChain and LangGraph.

Despite the repository name, the current implementation is focused on a prompt-chaining article-generation workflow rather than a medical appointment application.

## Attribution

This repository is based on external source material published by UNIPDS and Erick Wendel.

Upstream material:
https://github.com/unipds-engenharia-de-ia-aplicada/engenharia-de-software-com-ia-aplicada

The package metadata and workflow originate from that source material. I keep the attribution explicit so the repository accurately represents its role as source-attributed technical implementation.

## What the project demonstrates

- LangGraph state workflows
- Prompt chaining
- Structured LLM outputs
- Conditional graph edges
- Reusable prompt templates
- OpenRouter integration
- Automated tests
- Environment-based configuration

## Current implementation

The workflow generates and reviews technical article content through multiple steps.

The implementation demonstrates orchestration patterns, state transitions and structured AI workflows. It should not be interpreted as an original medical scheduling system.

## Requirements

- Node.js 24.10 or newer
- OpenRouter API key

Create a local environment file from the provided example and install dependencies:

```bash
cp .env.example .env
npm ci
```

Run the available tests:

```bash
npm test
```

## Portfolio status

This repository is retained as an externally sourced reference implementation. It is intentionally separated from original flagship work.


## License and distribution

The upstream source repository is published under CC BY-NC-ND 4.0. Its LICENSE.md states that modified or adapted versions may not be distributed under the NoDerivatives condition. This repository is therefore not presented as a permissively licensed open-source derivative. See [NOTICE.md](NOTICE.md) for the provenance and licensing note.
