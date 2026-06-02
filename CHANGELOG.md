# @tammergard/prettier-config

## 3.0.2

### Patch Changes

- ef0e005: Use `devEngines` instead of `engines` for the Node version requirement, so it applies to development only and no longer constrains consumers of the package.

## 3.0.1

### Patch Changes

- f727af6: Align project configuration with other `@tammergard/*` packages: rename
  `.prettierrc.js` to `.prettierrc.mjs`, sort `package.json` keys, declare
  `engines.node >= 24`, switch release workflow to npm trusted publishing, and
  update the changesets schema URL to match the actually installed version.

## 3.0.0

### Major Changes

- 42f5b46: Require Prettier 3+. The config has been ESM-only since 2.1.0, which does not work with Prettier 2.

## 2.1.0

### Minor Changes

- 749345f: Migrate to ESM

## 2.0.2

### Patch Changes

- 2cc65c5: Support Prettier v3

## 2.0.1

### Patch Changes

- 63ee58f: Add provenance.
