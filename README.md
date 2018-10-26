# Remark Config

[![version][npm-image]][npm-url] [![Build Status][circle-image]][circle-url]

> remark preset to configure `remark-lint` with settings that inherit from [`remark-preset-lint-markdown-style-guide`][remark-preset-lint-markdown-style-guide] with some customization for usage at TELUS.

## Usage

###### 1. Install

```sh
npm install --save-dev remark-cli @telus/remark-config
```

###### 2. Configure

include a `.remarkrc` file in your project root directory:

```json
{
  "plugins": [
    "@telus/remark-config"
  ]
}
```

###### 3. Run

```sh
remark --quiet --frail .
```

###### 4. Add to your `npm scripts` (recommended)

```json
"scripts": {
  "lint:markdown": "remark --quiet --frail ."
  ...
}
```

---
> Github: [@telus](https://github.com/telus) &bull; 
> Twitter: [@telusdigital](https://twitter.com/telusdigital)

[circle-url]: https://circleci.com/gh/telus/remark-config
[circle-image]: https://img.shields.io/circleci/project/github/telus/remark-config/master.svg?style=for-the-badge&logo=circleci

[npm-url]: https://www.npmjs.com/package/@telus/remark-config
[npm-image]: https://img.shields.io/npm/v/@telus/remark-config.svg?style=for-the-badge&logo=npm


[remark-preset-lint-markdown-style-guide]: https://github.com/remarkjs/remark-lint/tree/master/packages/remark-preset-lint-markdown-style-guide
