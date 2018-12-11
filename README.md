# tsconfig

Base tsconfig setttings

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```
$ npm install --save-dev @jaredmpeterson/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@jaredmpeterson/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "lib": ["es2018"]
  }
}
```

## License

MIT © [Jared M. Peterson](https://www.jaredmpeterson.com)
