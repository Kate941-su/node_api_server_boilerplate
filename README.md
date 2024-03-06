# How to use it?

## Start with minimum configuration

1. Get Dependencies

Get dependencies from package.json

```shell
npm install
```

2. Launch Server

```shell
npm run start
```

The actual code is the below code that is written in `package.json`.

```shell
npx ts-node-dev --respawn --transpile-only --exit-child server.ts
```

3. Check Your Helth of Server

```shell
curl  http://localhost:8000/api/healthchecker
```
