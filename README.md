# @tammergard/prettier-config

A sharable Prettier config with personal preferences.

## Installation

Install this Prettier config together with its peer dependencies:

```bash
# npm
npm install @tammergard/prettier-config prettier --save-dev

# yarn
yarn add @tammergard/prettier-config prettier --dev

# pnpm
pnpm add @tammergard/prettier-config prettier --save-dev
```

## Usage

Add the config to your Prettier config file:

```js
import tammergardPrettierConfig from "@tammergard/prettier-config"

export default {
	...tammergardPrettierConfig,
}
```

## License

MIT
