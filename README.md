# eslint-plugin-tailwind-token-lint

linter for tailwind css token

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-tailwind-token-lint`:

```sh
npm install eslint-plugin-tailwind-token-lint --save-dev
```

## Usage

Add `tailwind-token-lint` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["tailwind-token-lint"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "tailwind-token-lint/rule-name": 2
  }
}
```

## Configurations

<!-- begin auto-generated configs list -->

TODO: Run eslint-doc-generator to generate the configs list (or delete this section if no configs are offered).

<!-- end auto-generated configs list -->

## Rules

<!-- begin auto-generated rules list -->

TODO: Run eslint-doc-generator to generate the rules list.

<!-- end auto-generated rules list -->
