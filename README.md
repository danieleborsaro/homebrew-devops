# Homebrew DevOps Tap

Custom Homebrew formulae for DevOps utilities, command-line tools, and automation scripts.

## Installation

You can tap this repository to install any of the available tools:

```bash
brew tap danieleborsaro/devops
```

Once tapped, you can install individual tools normally:

```bash
brew install danieleborsaro/devops/yago
```

Alternatively, you can install directly via URL without tapping first:

```bash
brew install danieleborsaro/devops/yago
```

## Available Formulae

| Formula | Description |
| --- | --- |
| [`yago`](https://www.google.com/search?q=Formula/yago.rb) | GitOps tool for non-kubernetes platforms. |

## Updating

To update your tap and installed tools to the latest versions:

```bash
brew update
brew upgrade yago
```

## Troubleshooting & Local Testing

If you are developing or testing formula updates locally in this tap, you can run Homebrew's official linter to check for syntax or style errors:

```bash
brew audit --strict --online Formula/yago.rb
brew style Formula/yago.rb
```
