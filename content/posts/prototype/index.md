---
title: "Prototype"
date: 2022-03-30
publishdate: 2022-03-30
resources:
- name: featuredImage
  src: "cover.png"
---
### Let's take a look at my prototype so far!
 
This prototype shows that I could develop this idea if given enough time. While completing this prototype, I had to learn many new things and do things I have never done before. If I could get this done in a week, imagine how much I could get done in a month or more! The assets I have developed for this prototype can be applied to making a game that procedurally generates the game's map. While this is not a finished game, this prototype serves as an experiment with a type of level generation.
 
So far, this prototype contains floor and wall prefabs, a player prefab, a level generator script (with color mapping helper script), a player movement script, and a camera follow script.

### Features

This prototype contains simple rooms with minimal graphics to display the game map. Currently, this project is not a completed game, and rather a collection of assets I have developed. These assets are being designed to drive the main features that would be in a finished game.

### Installation requirements

Currently you will need Unity on your machine in order to utilize my assets. You may also need photo editing or drawing software to create a PNG of the level layout you want to generate.

### How to run prototype

With the assets in your Unity project, you will need to add a LevelGenerator prefab to your Scene. You'll see that the LevelGenerator has a Level Generator component. This component has two important variables: Map and Color Mappings. Just as an example, I have included a map PNG from the Sprites/Maps folder to use as the map. You can click and drag any map sprite PNG into the Map variable of this component. The Level Generator will iterate through the PNG you give it, and look for the colors of the pixels in the picture. Inside the Color Mappings, you will see that certain colors are linked to existing prefabs. For example, black is linked to the Wall prefab, while gray is linked to the floor prefab (these can be found in the Prefabs folder). When using your own map PNG, be sure to update the Color Mappings to match your desired design. Keep in mind that the colors **must** be an exact match; be sure to check the RGB values! Once you're ready, hit the play button on the top of the Unity editor. You will see that the level has been generated!

Note: When adding your own map sprite PNGs into your Unity project, be sure to turn on 'Read/Write Enabled', change 'Filter Mode' to Point (no filter), and 'Compression' to None. The **most important** thing to do is turn on 'Read/Write Enabled'! If you don't, LevelGenerator will not be able to access the PNG and the program will throw an error.

### References

I used a series of YouTube tutorials when developing my C# Unity scripts:

How to make a LEVEL EDITOR in Unity: https://youtu.be/B_Xp9pt8nRY
Smooth Camera Follow in Unity - Tutorial: https://youtu.be/MFQhpwc6cKE
TOP DOWN MOVEMENT in Unity!: https://youtu.be/whzomFgjT50
