# ts-toolkit-cli

Learning TypeScript by building tiny CLIs

Small but I use it weekly.

## Install

```bash
npm install
npm run build
```

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## What it does

- commander-based subcommands
- Ships as an ESM binary
- npm link friendly
- Strict tsconfig, no any

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── usage.md
├── src/
│   └── index.ts
├── .gitignore
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.
