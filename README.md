# Yosys-Action

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

Install & add oss-cad-suite to PATH, including Yosys, SymbiYosys and so on.

## Quick Usage

1. Create `.github/workflows/main.yml`
2. Paste it in `main.yml`

```yaml
name: ci

on:
  push:
  pull_request:
  workflow_dispatch:

jobs:
  ci:
    runs-on: ubuntu-latest
    steps:
      - uses: kazutoiris/yosys-action@v1
```
