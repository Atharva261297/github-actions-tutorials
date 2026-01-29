# GitHub Actions Tutorials

A curated collection of GitHub Actions workflows demonstrating essential CI/CD concepts and best practices. These tutorials are designed to help developers understand and implement automated workflows for their projects.

## Overview

This repository contains progressively advanced GitHub Actions workflows with practical examples. Each workflow illustrates specific concepts and features of GitHub Actions, from basic automation to comprehensive CI/CD pipelines.

## Workflows

### 1. Hello GitHub Actions
**File:** [.github/workflows/1-hello-actions.yml](.github/workflows/1-hello-actions.yml)

The simplest GitHub Actions workflow. Demonstrates:
- Basic workflow structure
- Triggering on push events
- Running a simple shell command

**Concepts:** Workflow syntax, events, jobs, steps

### 2. Multi-OS Matrix Workflow
**File:** [.github/workflows/2-matrix-os.yml](.github/workflows/2-matrix-os.yml)

Build and test across multiple operating systems simultaneously. Demonstrates:
- Matrix strategy for parallel execution
- Testing on Ubuntu, Windows, and macOS
- Dynamic variable interpolation

**Concepts:** Matrix builds, cross-platform testing, environment flexibility

### 3. Scheduled Cron Workflow
**File:** [.github/workflows/3-scheduled-workflow.yml](.github/workflows/3-scheduled-workflow.yml)

Automate tasks on a schedule. Demonstrates:
- Cron scheduling syntax
- Manual workflow triggers
- Time-based automation

**Concepts:** Scheduled workflows, cron expressions, workflow_dispatch

### 4. Environment Variables Demo
**File:** [.github/workflows/4-env-variables.yml](.github/workflows/4-env-variables.yml)

Manage configuration and secrets across different scopes. Demonstrates:
- Global workflow-level environment variables
- Job-level variables
- Step-level variable overrides
- Variable accessibility and scope

**Concepts:** Environment variable scoping, configuration management, variable precedence

### 5. Node.js CI Pipeline
**File:** [.github/workflows/5-node-ci.yml](.github/workflows/5-node-ci.yml)

Complete CI/CD pipeline for Node.js projects. Demonstrates:
- Code checkout
- Node.js environment setup
- Dependency caching
- Linting and testing automation
- Pull request triggers

**Concepts:** CI/CD pipelines, dependency caching, code quality checks, test automation

## Sample Application

The [hello-world-node](hello-world-node/) directory contains a simple Node.js application used with the CI/CD workflows. It includes:
- Basic Express or Node server implementation
- ESLint configuration for code quality
- Test suite for validation
- Automated workflow integration

## Getting Started

1. **Explore the workflows:** Review the YAML files in `.github/workflows/` to understand each concept
2. **Study incrementally:** Start with workflow 1 and progress through the more complex examples
3. **Apply to your project:** Adapt these workflows to your own repositories
4. **Extend and customize:** Use these as templates for your specific CI/CD needs

## Prerequisites

- GitHub repository with Actions enabled
- Basic understanding of YAML syntax
- For the Node.js example: Node.js 18+ installed locally

## Key Concepts Covered

- **Workflow Triggers:** Push events, pull requests, scheduled runs
- **Job Configuration:** Runners, strategies, environment setup
- **Steps and Actions:** Built-in and community actions, shell commands
- **Variables and Secrets:** Environment variables, GitHub secrets
- **Matrix Builds:** Testing across multiple configurations
- **Caching:** Optimizing workflow performance
- **Code Quality:** Linting and automated testing

## Best Practices

- Keep workflows modular and focused on single responsibilities
- Use caching to improve workflow performance
- Leverage GitHub's official actions for common tasks
- Secure sensitive data using GitHub Secrets
- Test workflow changes in a branch before merging
- Document complex workflows with comments
- Use descriptive names for jobs and steps

## Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
- [Workflow Syntax Reference](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)

## Contributing

Feel free to suggest improvements or additional workflow examples. These tutorials are meant to be educational and extensible.

## License

MIT
