# Batch Factory

A foundational scaffold for the BatchFactory challenge. Use this repository to build your implementation from scratch.

📋 [View Challenge](https://cloudchallenges.hyperoot.dev/challenge/batchfactory) · 📖 [Read Solution Guide](https://cloudchallenges.hyperoot.dev/challenge/batchfactory/solution)

## Architecture

![Architecture](./assets/batchfactory.svg)

## Your Work Area

This starter is structured so you can focus only on the parts required for solving the challenge.

```shell
└── samples/              # Input and test data
```

You may create additional folders as needed for your solution.

Everything else in this repository exists only to support development, collaboration, and tooling.

## Getting Started

Before doing anything else, **fork this repository**. This ensures you have full control of your own workspace and can push commits freely.

```shell
# After pressing Fork on GitHub:
git clone https://github.com/<your-username>/<repo-name>
cd <repo-name>
```

Once you have your own copy locally, choose one of the two paths below.

### **Option 1: Use Dev Container (Recommended - Easiest)**

This is the simplest and most reliable setup.
All tools are installed automatically, and setup scripts run without you touching anything.

#### Requirements

- Docker installed and running
- VS Code installed
- Dev Containers extension installed

#### Steps

1. Open the repository folder in VS Code
2. VS Code will detect `.devcontainer/`
3. Select **"Reopen in Container"** when prompted
4. The development environment is ready - no scripts required

**Important:**

- `setup.sh` runs automatically via the devcontainer post-create hook
- `enter_project.sh` is handled automatically via Mise’s directory hooks
- You do **not** need to run either script manually in this workflow

### **Option 2: Local Development (Manual Setup)**

If you do not want to use Dev Containers, you can work locally.

#### 1. Install required tools

You have two ways to install the tools needed for this project:

##### a) **Install Mise (recommended)**

Mise automatically installs all tool versions defined in `mise.toml`.

Install Mise → [https://mise.jdx.dev](https://mise.jdx.dev)

Then run:

```shell
mise install
```

##### b) **Install tools manually**

You may manually install the relevant tool versions:
Terraform, Python, Node, AWS CLI, etc., depending on the challenge.

#### 2. Enter the project environment

If using Mise:

```shell
./scripts/enter_project.sh
```

This ensures tool versions, environment variables, and hooks are loaded.

> Everything below is optional technical support content

## Repository Structure

```shell
├── .devcontainer/        # Optional Dev Container setup
├── .github/              # Issue/PR templates & workflows
├── docs/                 # Optional notes or guidance
├── scripts/              # Setup and environment helper scripts
├── mise.toml             # Toolchain definition
└── README.md
```

## Explanation of Other Files

These files support development workflows but are not required for deploying or testing the solution.

- **`.devcontainer/`** → Reproducible VS Code development environment → [https://containers.dev](https://containers.dev)

- **`.pre-commit-config.yaml`** → Ensures formatting, linting, static checks → [https://pre-commit.com](https://pre-commit.com)

- **`.github/`** → Contains issue templates, PR templates, CODEOWNERS, and workflow automation → [https://docs.github.com/repositories](https://docs.github.com/repositories)

- **`mise.toml`** → Defines the toolchain versions required for this solution → [https://mise.jdx.dev](https://mise.jdx.dev)

- **`scripts/`** → Helper scripts

## License

See [LICENSE](./LICENSE) for details.

## Support

If you find this helpful, consider supporting my work ❤️

[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor-GitHub-ea4aaa?style=for-the-badge\&logo=github)](https://github.com/sponsors/HYP3R00T)
