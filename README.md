# Prax Wallet Configs

This repo contains all of the configs that are shared across the Prax ecosystem. Currently ESLint, soon Prettier.

## Consuming this repo

1. Install the repo using your package manager.
```bash
pnpm add prax-wallet/configs#main
```

This will keep the configs up to date by always pulling from master

2. Extend the relevant config

In your `eslint.config.js`:
```javascript
import eslintConfig from 'configs/eslint';


export default [
  eslintConfig,
  // configuration overrides
];
```
