# Demo of TS & ESLint Error

## System

- Node v16.15.1
- NPM v8.14.0
- ESLint 8.22

## How to

```bash
npm install
npm run lint
```

## Versions

To change between the broke and working version, edit the `package.json` file
with the changes in this section.

```json
{
  "devDependencies": {
    "@typescript-eslint/eslint-plugin": "5.33.0",
    "@typescript-eslint/parser": "5.33.0",
  }
}
```

### Working

- typescript-eslint/plugin 5.33.0
- typescript-eslint/parser 5.33.0

### Broke

- typescript-eslint/plugin 5.34.0
- typescript-eslint/parser 5.34.0
