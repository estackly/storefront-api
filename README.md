# Estackly Storefront API

The OpenAPI 3.1 description of the Estackly Storefront API: catalogue, carts, hosted checkout links, customer accounts, store content and webhooks.

- Documentation and guides: https://developers.estackly.com
- Interactive reference: https://developers.estackly.com/reference
- Live spec: https://api.estackly.com/storefront/openapi.yaml

## Use it

Generate a client in any language with [OpenAPI Generator](https://openapi-generator.tech):

```sh
npx @openapitools/openapi-generator-cli generate -i openapi.yaml -g python -o estackly-python
```

For JavaScript and TypeScript, use the official SDK: [estackly/storefront-js](https://github.com/estackly/storefront-js).

## Starters

- [estackly/nextjs-storefront](https://github.com/estackly/nextjs-storefront): a headless storefront built with Next.js.

## Issues

Found a mistake in the spec or a missing endpoint? Open an issue in this repository.
