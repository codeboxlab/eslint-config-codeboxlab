# CodeBoxLab ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- Import Helpers
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies

```bash
# With npm
npm i -D eslint @codeboxlab_/eslint-config

# With yarn
yarn add -D eslint @codeboxlab_/eslint-config
```

2. Create a `.eslintrc.json` (or `.eslintrc`) file extending the config:

```
{
  "extends": "@codeboxlab_/eslint-config"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
