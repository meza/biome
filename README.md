# biome

Reusable Biome Config

`pnpm add -D @meza/biome`

```json
{
  "extends": ["@meza/biome"]
}

```

Notable rules included:

- `complexity/noExcessiveCognitiveComplexity` (max 15)
- `complexity/noExcessiveLinesPerFunction` (max 80, skipping blank lines)
- `correctness/noNestedComponentDefinitions` (React-only)
