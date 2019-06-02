# OctoPrint-Tempsgraph

This Plugin is a fork of https://github.com/1r0b1n0/OctoPrint-Tempsgraph
It has been modified to use more of my screen's width.
Currently it is set to 720x1280, and depends on using Theameify to set .span8|width to "1310"
Eventully I would like to use the setting dialouge to control the size, or inherit the size from .span8 and settings.

This plugin adds some functionaly to the temperature graph :
* exact values on hover
* zooming
* panning
* export

![Preview: zoom](/extras/zoom.png)
![Preview: hover](/extras/hover.png)
![Preview: dark theme](/extras/dark_theme.png)

## Usage :
* hover over the graph to show date and temperatures under the cursor
* drag to zoom
* shift + drag to pan
* double click to reset axes / autoscale

## Setup

Install manually using this URL:

    https://github.com/drewoprea/OctoPrint-Tempsgraph/archive/master.zip

## Configuration

When the plugin is enabled, it will replace the temperature graph.
In the settings, "Features / Enable temperature graph" must of course be activated.
