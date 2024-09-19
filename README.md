# tsconfig

> Shared TypeScript config for my MapColonies

## Install

```bash
npm install --save-dev @map-colonies/tsconfig
```

The config requires TypeScript 5.5 or later.

## Usage

`tsconfig.json`

```json
{
  "extends": "@map-colonies/tsconfig/<wanted tsconfig file>"
}
```

## Available files

- `tsconfig-app.json` - For use in services like ts-server-boilerplate
- `tsconfig-library.json` - For use in libraries published top npm
- `tsconfig-base.json` - The base tsconfig file
