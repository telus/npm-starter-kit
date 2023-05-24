![maintenance-status](https://img.shields.io/badge/maintenance-deprecated-red.svg)
![npm](https://img.shields.io/npm/v/@telus/remark-config)

# Remark Config

Remark preset to configure `remark-lint` with settings that inherit from [`remark-preset-lint-markdown-style-guide`](https://github.com/remarkjs/remark-lint/tree/master/packages/remark-preset-lint-markdown-style-guide) with some customization for usage at TELUS.

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
