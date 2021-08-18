---
title: Overview
nav_order: 2
---

# Overview
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

The main sections are shown in the figure below:
<div style="text-align:center">
    <video width="900" controls playsinline autoplay muted loop>
        <source src="images/UsingPSRIOGraphIHM.webm" type="video/webm">
        Your browser does not support the video tag.
    </video>
</div>

1. Menu
2. Workspace
3. Selection panel
4. Simulation panel
5. Values panel

## Menu

The menu provides extra functionalities, which are described below.

### View menu

* Refresh: refreshes the workspace with the current selected variables
* Show selection panel: show/hides the selection panel
* Show simulation panel: shows/hides the simulation panel
* Show values panel: shows/hides the values panel.
* Hide all panels: hides all panels and show only the workspace area.
* Circuit exhibition mode:
  * Schematic diagram: represents the circuits as continuous straight lines connnecting their terminal buses.
  * Geo-referenced: represents the circuits as continuous segments connecting each onde of the informed coordinates along the circuit path. The circuits without read coordinates available are represented schematically as a straight dashed line.

### Geographical coordinates menu

* Generate coordinates: uses an internal algorithm to generate artificial coordinates for all buses, replacing the current ones. This is convenient for a preliminary analysis in case the real coordinates are not available

### Search menu

* Search bus: searches for a bus and place it on the center of the workspace.

## Workspace

The *workspace* is the main component of the graphical interface. In this area, Power View graphically displays buses and circuits of the network as well as selected transmission-related results of PSR models. Variables are displayed on map, in a georeferenced and integrated environment.

Power View relies on the navigation functionality provided by *Google Maps* API and, in this way, you can move around the map and change the zoom level to highlight the geographical areas of interest.

## Selection panel

The selection panel shows for each group of agents (system, bus and circuit) two sub-panels that allow the user to select the variables and agents to be displayed in the workspace.

### Available variables sub-panel

* Variables list: shows a list with all the variables associated to the selected group.
* Name: displays the name of the selected variable.
* Selected for showing: enables the graphical representation of the selected variable in the workspace.
* Exhibition mode: graphical options to display the selected variable for each agent in the workspace.
* Selected color: defines the color of the selected variable in the workspace.
* No fill: defines that the graphical representation in the workspace must be transparent
* Scale: defines the scale of the graphical representation of the selected variable in the workspace.

### Agents configuration sub-panel

* Agents list: shows a list with all the agents associated to the selected group.
* Name: displays the name of the selected agent.
* Selected for showing: enables the graphical representation of the selected agent in the workspace.

## Simulation panel

The simulation shows the controls related to chronological evolution of simulation variables, where the user defines the stage to visualize and/or "play" an animated chronological evolution of the simulation variables along the study period. It is possible to adjust the animation speed accordingly to the user's needs.

The following controls are available:

### Playback controls

* Pause: pauses the execution at the current stage.
* Play: stars the execution from the current stage in forward direction.
* Backward: moves to the previous stage.
* Forward: moves to the next stage.
    * Repeats simulation after last stage

### Other controls

* Speed/Simulation: speed of the chronological time evolution.
* Speed/Animation: speed of the graphical changes in the variables.
* Scenario: selection of the desired scenario for visualization.
* Block: selection of the desired block for visualization.
* Show aggregated: displays the average values per scenario and the weighted average value per block.
* Stage: displays the current stage displayed on the workspace.

## Values panel

Displays the numerical values of the selected variables for the agents selected with the mouse.
