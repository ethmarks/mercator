# Greenland Distortion Demo

![Interactive map showing Greenland highlighted in green, demonstrating the Mercator projection distortion effect](greenland-screenshot.png)

A simple interactive web application that demonstrates how the Mercator projection distorts the size of landmasses at different latitudes.

## What it does

- Shows Greenland on an interactive map
- Allows you to drag Greenland to different locations around the world
- Automatically scales Greenland to show how it would appear at different latitudes due to Mercator projection distortion
- Demonstrates why Greenland appears so large on most world maps (because it's near the poles where distortion is greatest)

## How to use

1. Visit <https://ethmarks.github.io/mercator/greenland/>
2. Click and drag the green Greenland shape to move it around the map
3. Watch how Greenland's apparent size changes as you move it to different latitudes
4. Notice how it appears much smaller near the equator and larger near the poles

## Technical details

Built with:
- Leaflet.js for the interactive map
- D3.js for geographic projections and coordinate transformations
- Natural Earth geographic data for Greenland's shape
- Vanilla JavaScript for the drag-and-drop functionality

The application calculates the appropriate scaling factor based on the Mercator projection's distortion at different latitudes and applies it in real-time as you drag Greenland around.
