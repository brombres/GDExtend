# GDExtend
A Rogo buildscript to facilitate creating and building GDExtensions for Godot 4.

About     | &nbsp;
----------|-----------------------
Version   | 1.0
Date      | June 26, 2023
Platforms | Windows, macOS, Linux

# Installation

1. Install [Morlock](https://morlock.sh). Installing Morlock will also install the [Rogue](https://github.com/brombres/rogue) language and the [Rogo](https://github.com/brombres/Rogo) build tool.

2. Place the `BuildCore.rogue` buildscript into a new GDExtension project folder in one of the following ways:

    - Copy and paste [BuildCore.rogue](BuildCore.rogue) into the project folder.
    - Fork this repo as your new GDExtension project.
    - Use `curl` to fetch `BuildCore.rogue` and save it in the current folder.

            curl -O https://raw.githubusercontent.com/brombres/GDExtend/main/BuildCore.rogue

3. Run 'rogo'. On the first build, the script will guide the user through creating the extension framework and the first native class. It will also download the necessary [godot-cpp](https://github.com/godotengine/godot-cpp) repo and perform an initial build of the extension.

# Usage

Run `rogo help` to see a list of available commands or e.g. `rogo help build` for extended information on a specific command.

