# My shared TypeScript config

## Installation

```bash
pnpm add -D typescript @skarab/typescript-config
```

## Usage

Add `@skarab/typescript-config` to the extends section of your TypeScript configuration file.

```json
{
  "extends": "@skarab/typescript-config",
  "compilerOptions": {
    "outDir": "build",
    "noEmit": false // true by default
  }
}
```

# My other shared configurations

- [@skarab/eslint-config](https://github.com/skarab42/eslint-config)
- [@skarab/prettier-config](https://github.com/skarab42/prettier-config)
