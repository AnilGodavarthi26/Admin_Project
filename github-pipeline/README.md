# GitHub Actions Pipeline - Java Maven Project Creator

This workspace contains a GitHub Actions workflow that creates a Java Maven project and pushes it to GitHub with dynamic authentication.

## Project Structure

```
.
├── .github/
│   └── workflows/
│       └── create-maven-project.yml    # Main workflow file
├── README.md                            # This file
└── copilot-instructions.md            # Copilot workspace instructions
```

## Workflow Features

- **Manual Trigger** — Run on-demand via workflow_dispatch
- **Dynamic Inputs** — Repository name and visibility (public/private)
- **Auto Java Setup** — JDK 17 with Maven
- **Dynamic Authentication** — Uses GitHub token for secure push
- **Repository Creation** — Creates new repo via GitHub CLI

## How to Use

1. Push this workflow to your GitHub repository
2. Go to **Actions** → **Create and Push Java Maven Project**
3. Click **Run workflow**
4. Enter repository name and visibility
5. Watch the workflow create and push your Maven project

## Configuration

| Input | Description | Default |
|-------|-------------|---------|
| `repo_name` | Name of repository to create | my-java-maven-project |
| `repo_visibility` | Public or private | private |

## Authentication

- Uses `secrets.GITHUB_TOKEN` (auto-provided by GitHub)
- For external repos, add a PAT as a secret

## Requirements

- GitHub CLI (`gh`) installed
- Repository creation permissions
- GitHub Actions enabled