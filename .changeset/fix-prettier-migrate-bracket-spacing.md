---
"@biomejs/biome": patch
---

Fixed `biome migrate prettier` ignoring the Prettier option `bracketSpacing` for the top-level `formatter`. The option was previously applied only to JavaScript, so JSON and GraphQL files were still formatted with spaces inside braces after the migration.
