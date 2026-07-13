# The Burning Of Isaac Remake

A clone of the game The Binding Of Isaac.

## Description

Made for educational purposes as a second attempt to recreate the popular game in Java.
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
* Can be built using any standard Java IDE. No external build tool required — compiled via IntelliJ's built-in build system.
* Java JDK 17 is needed to build the project.
* Open the project in IntelliJ, set src/tboir/Main.java as the run configuration if not already set, and click Run. Or any equivalent approach using other tools.

## Project History

This is the second of three tboi clone projects.
* The [first](https://github.com/MrMethor/tboi-basic), a more basic version also made in java. 
* The second being this project
* The [third](https://github.com/MrMethor/tboi-modular), a modular version with separated Engine, CLI and UI in C#. 

## License
[MIT](https://github.com/MrMethor/tboi-remake/blob/master/LICENSE)
