# Example Mod (Fabric, Minecraft 1.21.11)

## Build the zip
Requires Java 21.

```
./gradlew build        # Windows: gradlew.bat build
```

Output: `build/distributions/examplemod-1.0.0-mc1.21.11.zip` (contains `mods/examplemod-1.0.0.jar`).

Run only the zip task: `./gradlew packageZip`. Test in-game: `./gradlew runClient`.
