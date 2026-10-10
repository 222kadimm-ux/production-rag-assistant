# Contributing to Production RAG Assistant

Thank you for your interest in contributing! This document provides guidelines for contributing to this project.

## How to Contribute

### Reporting Bugs

If you find a bug, please open an issue using the **Bug Report** template. Include:
- A clear description of the problem
- Steps to reproduce
- Expected behavior
- Your environment (OS, Python version, etc.)

### Suggesting Features

If you have an idea for a new feature, please open an issue using the **Feature Request** template. Include:
- A clear description of the feature
- Why it would be useful
- Any implementation ideas you have

### Submitting Changes

1. Fork the repository
2. Create a new branch (`git checkout -b type/short-slug`)
3. Make your changes
4. Run the local tests (see below)
5. Commit your changes (`git commit -m 'type: subject'`)
6. Push to the branch (`git push origin type/short-slug`)
7. Open a Pull Request

> **Note on CI:** If you are working from a fork, the CI pipeline may remain in a "waiting for status" state until a maintainer approves it. This is because GitHub does not pass secrets (like `GROQ_API_KEY`) to pull requests from forks. You may need to ping a maintainer to approve the workflow.

## Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/aieng-abdullah/production-rag-assistant.git
   cd production-rag-assistant