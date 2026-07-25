# 🧪 Example Mod

A starting point for building Minecraft mods — this is the official
[Fabric example mod](https://github.com/FabricMC/fabric-example-mod) template,
not yet customized.

Use it as a blank canvas for a new mod idea.

| | |
|---|---|
| Mod loader | Fabric |
| Minecraft | 26.1.2 |
| Java needed | 25 or newer |

## Build it

```bash
git clone https://github.com/cmadisons/example-mod.git
cd example-mod
./gradlew build
```

The finished mod appears in `build/libs/`.

## Turning it into your own mod

1. Rename `modid` in `src/main/resources/fabric.mod.json`
2. Change `name` and `description` in the same file
3. Change `maven_group` in `gradle.properties`
4. Rename the `com.example` package to your own

## Made by

Starbr0 · [@cmadisons](https://github.com/cmadisons)

License: CC0-1.0
