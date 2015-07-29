# esformatter-config-algolia

This is [Algolia](https://www.algolia.com/)'s [esformatter](https://github.com/millermedeiros/esformatter) configuration.

It will format your JavaScript code following the [algolia/eslint-config-algolia](https://github.com/algolia/eslint-config-algolia) rules.

## Wait, we have an automatic formatter according to this configuration

If you want to easily reformat your project according to our rules, see [algolia/jsfmt](https://github.com/algolia/jsfmt).

## How to use this configuration?

(really, just use [algolia/jsfmt](https://github.com/algolia/jsfmt))

In your project:

```sh
npm install esformatter \
  esformatter-config-algolia \
  esformatter-quotes \
  esformatter-semicolons \
  esformatter-parseint \
  esformatter-var-each \
  esformatter-eol-last \
  esformatter-spaced-lined-comment \
  esformatter-shebang-ignore \
  esformatter-remove-trailing-commas \
  --save-dev
```

In your package.json:

```json
{
  "scripts": {
    "jsformat": "esformatter -i -p default -c node_modules/esformatter-config-algolia/.esformatter"
  }
}
```
