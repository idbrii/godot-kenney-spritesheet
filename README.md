# Kenney Spritesheet Importer

[![Godot Version](https://img.shields.io/badge/Godot-4.4-blue)](https://godotengine.org/download/)

Supports Godot 4.1/4.2/4.4

[Kenny](https://kenney.nl/) has lots of sprite assets and many come with a spritesheet and an [Sparrow Texture Atlas XML Format](https://wiki.sparrow-framework.org/manual/textures_and_images) file that lists the locations of the sprites in that spritesheet. This plugin will take a spritesheet and generate:
* A folder full of AtlasTextures for the sprites in the spritesheet.
* An ImageTexture resource for the spritesheet so all AtlasTextures point to the same texture.

## Usage

Click on a png, and choose the 'Kenney Spritesheet' option under Import. Verify the options and (re)import.

![Find the Import tab and change to Kenney Spritesheet](https://bitbucket.org/repo/E8Lpey8/images/620792043-image.png)

## Files

This will take the spritesheet and use the provided xml from Kenney (with <TextureAtlas> and <SubTexture> nodes) and create AtlasTexture resource files into the destination folder. You can then use these textures in your project. They'll be named according to the names supplied in the xml file.

