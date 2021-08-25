---
title: Overview
nav_order: 2
---

# Overview
{: .no_toc }

The main sections are shown in the figure below:
<div style="text-align:center">
    <img src="images/powerview_img_sections.png" />
</div>

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## Quick access buttons
The quick access buttons provides extra functionalities, which are described below.

### Zoom control
* The Zoom control is a pair of +/- buttons for zooming in and out.

### Toggle menu
* Allows you to open and close the side menu after clicking the Toggle menu button. The goal is to hide the side menu, allowing you to display all map content

### Search menu
* Searches for an element (buses, circuits and dclinks) and place it on the center of the workspace.

### Diagram viewer
* Toggle circuit exhibition mode between *Schematic diagram* and *Geo-referenced*
    * Schematic diagram: represents the circuits as continuous straight lines connnecting their terminal buses.
    * Geo-referenced: represents the circuits as continuous segments connecting each onde of the informed coordinates along the circuit path. The circuits without read coordinates available are represented schematically as a straight dashed line.


## Workspace
The workspace is the main component of the graphical interface. In this area, Power View graphically displays buses and circuits of the network as well as selected transmission-related results of PSR models. Variables are displayed on map, in a georeferenced and integrated environment.

Power View relies on the navigation functionality provided by OpenLayers and, in this way, you can move around the map and change the zoom level to highlight the geographical areas of interest.

## Side menu
The menu provides extra functionalities, which are described below.

### Result selecion

The selection panel shows for each group of agents (system, bus and circuit) that allow the user to select the variables to be displayed in the workspace. 

* Variables list: shows a list with all the variables associated to the selected group.
* Selected for showing: enables the graphical representation of the selected variable in the workspace.
* Name: displays the name of the selected variable.
* Exhibition mode: graphical options to display the selected variable for each agent in the workspace.
* Selected color: defines the color of the selected variable in the workspace.
* No fill: defines that the graphical representation in the workspace must be transparent
* Scale: defines the scale of the graphical representation of the selected variable in the workspace.
	
### Agents list
Shows a list with all the agents associated to the selected group.

### Layers
A basemap provides a background of geographic context for the content in Workspace. Includes a basemap gallery with a variety of choices, including topography, imagery, and streets.


### Customization options
Allows you to modify general Power View settings.
	
## Simulation panel
The simulation shows the controls related to chronological evolution of simulation variables, where the user defines the stage to visualize and/or “play” an animated chronological evolution of the simulation variables along the study period. It is possible to adjust the animation speed accordingly to the user’s needs.

The following controls are available:
* Play/Pause: stars or pauses the execution from the current stage in forward direction.
* Stage: displays the current stage displayed on the workspace.
* Loop: Repeats simulation after last stage.
* Time slider: Drag the time slider to visualize the timeline animation.
* Configuration dataset: Open dataset configuration.

## Result panel
Displays the numerical values of the selected variables for the agents selected with the mouse.

## Dataset configuration 
* Scenario: selection of the desired scenario for visualization.
* Block: selection of the desired block for visualization.
* Show aggregated: displays the average values per scenario and the weighted average value per block.
