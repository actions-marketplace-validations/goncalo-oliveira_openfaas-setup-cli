# Setup OpenFaaS CLI

This action sets up OpenFaaS CLI for use in actions. Currently the installed version of the CLI is always the latest available.

## Usage

Basic Usage

```yaml
steps:
- uses: actions/checkout@v3
- uses: actions/openfaas-setup-cli@v1
- run: faas-cli version
```
