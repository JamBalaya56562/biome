---
"@biomejs/biome": patch
---

Fixed `biome migrate prettier` dropping the Prettier option `bracketSpacing` when it is set inside `overrides`. The option is now migrated to the `formatter.bracketSpacing` of the matching Biome override.
