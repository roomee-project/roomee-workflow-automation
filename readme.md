# Roomee Pre-commit


## System Requirements

You need a working copy of npm, the package manager that comes bundled with [Node.js](https://nodejs.org/en/).

Using npm, install ESLint:

```
npm install -g eslint
```

## Installation
Within a git repository, run the following command:
```sh
curl -s https://raw.githubusercontent.com/roomee-project/roomee-workflow-automation/master/bin/install | bash
```

## Usage
Roomee Precommit uses a pre-commit hook to run staged JavaScript files through ESLint before each commit.


To skip Roomee Precommit, commit with the `--no-verify` option.