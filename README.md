# ezHomes
> A customizable Spigot Minecraft plugin for setting, removing, and going to your homes with a nice GUI

## Commands

> The commands that are included in the plugin

- /home (or /homes)
  - It can open the GUI or directly teleport you to a home
- /delhome (or /remhome)
  - It deletes the specified home
- /sethome
  - It sets a home

## Permissions

> The permissions that are used for features in the plugin

> Note that all current command permissions are given by default to all players

- ezhomes.home
  - Permission for the /home (or /homes) command
- ezhomes.delhome
  - Permission for the /delhome (or /remhome) command
- ezhomes.sethome
  - Permission for the /sethome command
- ezhomes.homelimit.#
  - The permission for how many homes a player can have at a time
  - Replace `#` with an integer 1-5

## Versions

ezHomes is tested on Minecraft Java version 1.21.4 on a PaperMC server but might be tested on other versions in the future

## Compiling

To compile you must have Gradle then run `./gradlew build` in your terminal

**This is _only_ tested in Windows**
