# @tammergard/prettier-config

A sharable Prettier config with personal preferences. Requires Prettier 3 or
later.

## Installation

```bash
# npm
npm install --save-dev @tammergard/prettier-config prettier

# pnpm
pnpm add -D @tammergard/prettier-config prettier

# bun
bun add -d @tammergard/prettier-config prettier
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
