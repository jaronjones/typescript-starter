# TypesScript Basic Starter
## Initial Setup
`npm init -y`

## Setup Typescript
```
yarn add typescript --dev
yarn add @types/node --dev
```

## Create tsconfig
`npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true`