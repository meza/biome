# @meza/biome

Reusable Biome Config.

This config is meant to be extremely strict to catch as many issues as possible.
Its goal is to ensure that whatever goes out into production is as clean and performant as possible.
Nitpicky, obnoxious, and pedantic.

The included biome rules should be regularly updated to reflect the latest best practices and performance optimizations.
As biome gets updated, the rules will need to be updated as well, so be sure to check the repo for updates.

`pnpm add -D @meza/biome`

```json
{
  "extends": ["@meza/biome"]
}

```
