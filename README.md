# TypeScript Basic Starter
## Initial Setup
```
npm init -y
```

## Setup Typescript
```
yarn add typescript --dev
yarn add @types/node --dev
```

## Create tsconfig
```
npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true
```

## Useful Tools 
```
yarn add --dev ts-node nodemon
yarn add --dev rimraf
yarn add --dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin
yarn add --dev eslint-plugin-no-loops
yarn add --dev eslint-plugin-shopify
```