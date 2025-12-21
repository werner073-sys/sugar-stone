# Copilot Instructions for sugar-stone

## Project Overview

This is an early-stage repository currently containing minimal scaffolding. The project name suggests a focus on "sugar-stone" but specific domain, purpose, and architecture have not yet been established.

## Current Structure

- **Workflows**: Basic CI workflow at [.github/workflows/blank.yml](.github/workflows/blank.yml) - currently runs basic hello world on push/PR to main
- **Documentation**: Minimal README.md exists but needs expansion

## Development Guidelines

### CI/CD
- GitHub Actions workflow triggers on push and pull requests to the `main` branch
- Workflow runs on `ubuntu-latest` runners
- Currently executes placeholder commands - update this workflow as the project develops

### Getting Started

Since the project is in early stages:
1. Define the project's purpose and update README.md with clear documentation
2. Establish the technology stack and create appropriate configuration files
3. Update the CI workflow to include actual build/test steps relevant to your chosen stack
4. Add source code directories (e.g., `src/`, `lib/`, or language-specific structures)

### Branch Strategy
- **main**: Default branch protected by CI checks
- Create feature branches for new development

## What to Build Next

Consider establishing:
- Programming language and framework choice
- Project structure (source, tests, docs)
- Dependency management (package.json, requirements.txt, Cargo.toml, etc.)
- Testing framework and conventions
- Build and deployment processes
- Contribution guidelines

---

*Note: This file should be updated as the project architecture and conventions are established.*
