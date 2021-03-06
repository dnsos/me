---
layout: project
title: Climate Scenarios Viewer
ref: vks
permalink: "/climate-scenarios-viewer/"
tag: project
excerpt: Interactive Data Visualisation
external-link:
year: 2018
role: Concept, Design, Web Development
tools: D3.js
team: Hannah Schwan
supervision: Prof. Boris Müller
color-primary: '#f1f457'
order: 4
---

{:.m-image__fullwidth}
![Climate Scenarios Viewer: Closeup]({{site.baseurl}}/img/vks_intro.png)

{:.m-text__highlighted style="border-color: {{ page.color-primary }};"}
With climate change progressing, the world that we live in will change. We can not predict its exact transformation, but we can create scenarios that describe a range of possible futures. This tool allows comparison between various computed scenarios and aims to communicate the challenges that climate change brings.

## CONTEXT
As part of the [SENSES project](http://senses-project.org/) the _University of Applied Sciences Potsdam_ organised a course aiming to build tools to visualise climate scenarios. The data used stems from the _IIASA_ (International Institute for Applied Systems Analysis) and a comprehensible explanation of the characteristics of the different scenarios can be found in the [SENSES Primer](https://climatescenario.org/primer/).

This interactive scenario viewer is an approach to visualise the differences between computed climate scenarios and also to __communicate them to a broader public__. The variable group _Primary Energy_ was exemplarily used for this prototype.

{:.m-image__fullwidth}
![Climate Scenarios Viewer: Interface]({{site.baseurl}}/img/vks_general-interface.jpg)

## PROJECT
The result is a web-based interactive visualisation. It combines the common visualisation elements of a _bar chart_ and a _stacked bar chart_ and arranges them in a way that lets users explore __differences between scenarios without climate policies and ones that incorporate measures for mitigation and adaptation__.

Using the header it is possible to select different climate goals, the future in which they are to be achieved and years from 2020 to 2100.

{:.m-image__fullwidth}
![Climate Scenarios Viewer: Navigation]({{site.baseurl}}/img/vks_general-nav.png)

The visualisation immediately changes according to the selections.

{:.m-image__fullwidth .m-image__border}
![Climate Scenarios Viewer: Animation]({{site.baseurl}}/img/vks_general-animation.gif)

The bars' width corresponds to a value to be achieved (the goal) and its height to the difference between this goals' value and the value of the selected scenario. If the bar matches the horizontal green line both values are equal. The bars are colour-encoded: grey colours indicate that a goal is missed, green colour indicates that a goal is not only reached, but exceeded.

Hovering a bar displays a __tooltip__ with detailed information about the variable, the goal, the scenario and the deviation of the two values.

{:.m-image__fullwidth .m-image__border}
![Climate Scenarios Viewer: Mouseover]({{site.baseurl}}/img/vks_general-mouseover.png)

_The displayed version is an early prototype. A revision will be published soon._
