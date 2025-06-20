# @macklinu/typescript-library-template

> A little TypeScript library template using the tools and config I always set up

## Installation

```sh
pnpx degit macklinu/typescript-library-template [location]
# remove "private": true from package.json to enable publishing to npm
jq 'del(.private)' package.json | sponge package.json
```
