# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for WordPress plugins by Woda

## Install

```
npm install --save-dev @wwwoda/tsconfig
```

## Usage

`tsconfig.json`

```json
{
 "extends": "@wwwoda/tsconfig/tsconfig.json",
 "compilerOptions": {
  "outDir": "dist"
 }
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
 "extends": "@wwwoda/tsconfig/tsconfig.json",
 "compilerOptions": {
  "outDir": "dist",
  "target": "ES2021"
 }
}
```
