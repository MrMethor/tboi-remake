# The Burning Of Isaac Remake
## Description
Second iteretion of [The Binding Of Isaac](https://store.steampowered.com/app/250900/The_Binding_of_Isaac_Rebirth/) clones.
* Status - COMPLETE
* [Follow-up project](https://github.com/MrMethor/tboi-modular)

### Features
* Random dungeon map generation with few basic room types
* Two enemy types, a Fly (flies, follows player), a Body (pathfinds to player)
* 32 different items (differentiated by stats only e.g. Speed, Damage...)
* In game remappable player control scheme found in settings
* Responsive 2D movement, physics and combat

## Running
* Windows 10 is the targeted platform. Might or might not work with newer or older versions.
* Since it's made only using Java native library, only java JRE is needed which is already bundled with the release version. So no need for external downloads.
* The [release](https://github.com/MrMethor/tboi-remake/releases/tag/Runnable) contains both a portable and installer version. Both with identical content.
* To run the game open either the reburn.exe file or a system/desktop shortcut if installed using the installer.

## Building
* Can be built using any standard Java IDE. No external build tool required — compiled via [IntelliJ](https://www.jetbrains.com/idea/)'s built-in build system.
* [Java JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) is needed to build the project.
* Open the project in [IntelliJ](https://www.jetbrains.com/idea/), set src/tboir/Main.java as the run configuration if not already set, and click Run. Or any equivalent approach using other tools.

## Project History
This is the second of three tboi clone projects.
* The [first](https://github.com/MrMethor/tboi-basic), a more basic version also made in java. 
* The second being this project
* The [third](https://github.com/MrMethor/tboi-modular), a modular version with separated Engine, CLI and UI in C#.

## AI Disclosure
Generative AI has been used to create most of menu items including buttons and the background.

## [License](https://github.com/MrMethor/tboi-remake/blob/master/LICENSE)
