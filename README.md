# Storage🚌

[![CI](https://github.com/ducktors/storagebus/actions/workflows/ci.yml/badge.svg)](https://github.com/ducktors/storagebus/actions/workflows/ci.yml) [![CodeQL](https://github.com/ducktors/storagebus/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/ducktors/storagebus/actions/workflows/codeql-analysis.yml) [![OSSAR](https://github.com/ducktors/storagebus/actions/workflows/ossar-analysis.yml/badge.svg)](https://github.com/ducktors/storagebus/actions/workflows/ossar-analysis.yml)

Storagebus is a storage abstraction layer for Node.js that removes any difference among multiple public cloud storage services and local filesystems. 

## Contribute to this project
1. Clone this repository

    ```git clone git@github.com:github.com/ducktors/storagebus.git```

2. Move inside repository folder

    ```cd storagebus```

3. Install dependencies

    ```pnpm install```

4. Run the project in development mode

    ```pnpm dev```

## How to commit

This repo uses [Semantic Release](https://github.com/semantic-release/semantic-release) with Conventional Commits.
Releases are automatically created based on the type of commit message: feat for minor and fix for patch.

```
feat: new feature ---> 1.x.0
fix: fix a bug ---> 1.0.x
```
