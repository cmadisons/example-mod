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

## See the code

| File | What it does |
|---|---|
| 📄 [ExampleMod.java](src/main/java/com/example/ExampleMod.java) | Runs when Minecraft loads |
| 📄 [ExampleModClient.java](src/client/java/com/example/client/ExampleModClient.java) | Runs on the player's side |
| 📄 [ExampleMixin.java](src/main/java/com/example/mixin/ExampleMixin.java) | Changes how Minecraft itself behaves |
| 📄 [fabric.mod.json](src/main/resources/fabric.mod.json) | The mod's name, version, and what it needs |

## Build it

```bash
git clone https://github.com/cmadisons/example-mod.git
cd example-mod
./gradlew build
```

The finished mod appears in `build/libs/`.

> **Need Java 25.** Install with `brew install openjdk@25` if the build complains.

## Turning it into your own mod

1. Rename `modid` in [fabric.mod.json](src/main/resources/fabric.mod.json)
2. Change `name` and `description` in the same file
3. Change `maven_group` in [gradle.properties](gradle.properties)
4. Rename the `com.example` package to your own

## My other projects

⚾ [All Live Baseball](https://github.com/cmadisons/all-live-baseball) ·
🎮 [Minigames](https://github.com/cmadisons/minigames) ·
🌀 [Random Teleport](https://github.com/cmadisons/random-teleport)

Made by Starbr0 · [@cmadisons](https://github.com/cmadisons) · License: CC0-1.0
