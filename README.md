# Gama Labs ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @gamalabs/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@gamalabs/eslint-config/react"
  // "extends": "@gamalabs/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
