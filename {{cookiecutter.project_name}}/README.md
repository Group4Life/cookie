<h1 align="center">{{ cookiecutter.project_name.replace('-', ' ').title() }}</h1>

<p align="center"><em>{{ cookiecutter.project_description }}</em></p>

<p align="center">
  <a href="{{ cookiecutter.github_repository }}/actions/workflows/ci.yml">
    <img
      src="{{ cookiecutter.github_repository }}/actions/workflows/ci.yml/badge.svg"
      alt="CI"
    />
  </a>
  <a href="{{ cookiecutter.github_repository }}/actions/workflows/cd.yml">
    <img
      src="{{ cookiecutter.github_repository }}/actions/workflows/cd.yml/badge.svg"
      alt="CD"
    />
  </a>
  <a href="https://results.pre-commit.ci/latest/github/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/master">
    <img
      src="https://results.pre-commit.ci/badge/github/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/master.svg"
      alt="pre-commit.ci status"
    />
  </a>
  <a href="https://codecov.io/gh/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}">
    <img
      src="https://codecov.io/gh/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/branch/master/graph/badge.svg?token=coLOL0j6Ap"
      alt="Test Coverage"/>
  </a>
  <a href="https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url={{ cookiecutter.github_repository }}">
    <img
      src="https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode"
      alt="Open in GitHub Codespaces"
    />
  </a>
  <a href="https://github.com/Group4Life/cookie">
    <img
      src="https://img.shields.io/badge/cookiecutter-template-D4AA00.svg?style=flat&logo=cookiecutter"
      alt="Cookiecutter Template">
  </a>
  <a href="https://app.renovatebot.com/dashboard#github/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}">
    <img
      src="https://img.shields.io/badge/renovate-enabled-brightgreen.svg?style=flat&logo=renovatebot"
      alt="Renovate - Enabled">
  </a>
</p>

## :cd: Installation

In order to locally set up the project please follow the instructions below:

```shell
# Set up the GitHub repository
git clone {{cookiecutter.github_repository}}

# Create a virtual environment using poetry and install the required dependencies
poetry shell
poetry install

# Install pre-commit hooks
pre-commit install --install-hooks
```

## :sparkles: Contributing

Before contributing to the project, please go through the [Contributing Guidelines](https://{{cookiecutter.github_user}}.github.io/{{cookiecutter.project_name}}/latest/CONTRIBUTING/) first.

The project's documentation can be found [here](https://{{cookiecutter.github_user}}.github.io/{{cookiecutter.project_name}}/).
