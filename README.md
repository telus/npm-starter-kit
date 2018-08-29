# @telus/remark-preset-lint-markdown

remark preset to configure `remark-lint` with settings that inherit from [`remark-preset-lint-markdown-style-guide`][remark-preset-lint-markdown-style-guide] with some customization for usage at TELUS.

## Usage

###### 1. Install

```sh
npm install --save-dev remark-cli @telus/remark-preset-lint-markdown
```

###### 2. Configure

include a `.remarkrc` file in your project root directory:

```json
{
  "plugins": [
    "@telus/remark-preset-lint-markdown"
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

[remark-preset-lint-markdown-style-guide]: https://github.com/remarkjs/remark-lint/tree/master/packages/remark-preset-lint-markdown-style-guide
