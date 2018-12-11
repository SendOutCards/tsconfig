# tsconfig

Base tsconfig setttings

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```
$ yarn add -D @sendoutcards/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@sendoutcards/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "lib": ["es2018"]
  }
}
```

## License

MIT © [Send Out Cards](https://www.sendoutcards.com)
