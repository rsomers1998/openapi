Instructions for use of generator:

1. Run `npm run generate-api` to generate the base typescript code.
2. Replace all instances of `ClientResponse` with `IncomingMessage`.
3. Replace all instances of `All` with `all` and delete any accompanying imports.
4. `cd` into gen/api, update the version in package.json and run `npm run build`.