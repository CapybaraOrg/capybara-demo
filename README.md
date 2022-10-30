# Capybara Demo

Demo project using [capybara-action](https://github.com/CapybaraOrg/capybara-action)

## Requirements

The workflows need to use `workflow_dispatch`:

```yaml
on:
  workflow_dispatch:
```

The repository needs an environment (for example `main_environment`) where the secrets can be stored
and passed to the [capybara-action](https://github.com/CapybaraOrg/capybara-action)

## Usage

Please see [example-workflow.yml](.github/workflows/example-workflow.yml)
