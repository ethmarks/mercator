# Mercator's 1569 World Map Viewer

![High-resolution interactive viewer showing Mercator's original 1569 world map with deep zoom capabilities](seadragon-screenshot.png)

An interactive viewer for exploring Gerardus Mercator's original 1569 world map in stunning detail.

## What it does

- Displays Mercator's historic 1569 world map at a 10866x6900 pixel resolution
- Provides smooth zoom and pan functionality to explore fine details

## How to use

1. Visit <https://ethmarks.github.io/mercator/seadragon-viewer/>
2. Click and drag to pan around the map
3. Use your mouse wheel or touch gestures to zoom in and out
4. Explore the intricate details, decorative elements, and historical annotations on this 450+ year old map

## Technical details

Built with:
- OpenSeadragon for smooth deep zoom functionality
- Deep Zoom Image (DZI) format for efficient tile-based loading
- 5433x3450 scan of the original 1569 map sourced from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Mercator_1569_world_map_composite.jpg)
- Upscaled to double resolution using [Nomos8k](https://huggingface.co/Phips/4xNomos8kDAT)
