# Example Using create-react-app

See Pluralsight guide for more details and CRA docs on [adding TypeScript](https://facebook.github.io/create-react-app/docs/adding-typescript).

```bash
npx create-react-app my-typescript-app --typescript
```

Additional npm script for type checking tests:

```
"test:tsc": "tsc -p tsconfig.test.json -w"
```