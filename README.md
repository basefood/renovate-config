[![validate renovate config](https://github.com/basefood/renovate-config/actions/workflows/ci.yaml/badge.svg)](https://github.com/basefood/renovate-config/actions/workflows/ci.yaml)

# renovate-config

This repository contains the basic Renovate configuration that is used in all other basefood's repositories.

## Usage

Create file `renovate.json` in the root of the repository.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>basefood/renovate-config"]
}
```
