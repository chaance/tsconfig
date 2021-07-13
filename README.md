# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```
$ npm install --save-dev @chance/tsconfig
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@chance/tsconfig",
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@chance/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2021"
	}
}
```
