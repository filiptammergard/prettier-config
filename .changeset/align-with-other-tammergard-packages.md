---
"@tammergard/prettier-config": patch
---

Align project configuration with other `@tammergard/*` packages: rename
`.prettierrc.js` to `.prettierrc.mjs`, sort `package.json` keys, declare
`engines.node >= 24`, switch release workflow to npm trusted publishing, and
update the changesets schema URL to match the actually installed version.
