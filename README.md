[![npm](https://img.shields.io/npm/v/@marcelkloubert/tsconfig.svg)](https://www.npmjs.com/package/@marcelkloubert/tsconfig)
[![last build](https://img.shields.io/github/workflow/status/mkloubert/js-strings/Publish)](https://github.com/mkloubert/tsconfig/actions?query=workflow%3APublish)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/mkloubert/tsconfig/pulls)

# @marcelkloubert/tsconfig

Shared [TypeScript](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) config files, which can be used by anyone.

## Install

```
$ npm i -D @marcelkloubert/tsconfig
```

## Usage

### tsconfig.json

```json
{
  "extends": "@marcelkloubert/tsconfig",
  "compilerOptions": {
    "outDir": "lib",
    "rootDir": "src",
  },
  "exclude": ["node_modules"]
}
```

## License

MIT © [Marcel Joachim Kloubert](https://github.com/mkloubert)

## Support

<span class="badge-paypal"><a href="https://paypal.me/MarcelKloubert" title="Donate to this project using PayPal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/mkloubert" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/mkloubert" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>

Or visit https://marcel.coffee
