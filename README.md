![Logo](admin/material.png)
# ioBroker.material
=================

[![NPM version](http://img.shields.io/npm/v/iobroker.material.svg)](https://www.npmjs.com/package/iobroker.material)
[![Downloads](https://img.shields.io/npm/dm/iobroker.material.svg)](https://www.npmjs.com/package/iobroker.material)

[![NPM](https://nodei.co/npm/iobroker.material.png?downloads=true)](https://nodei.co/npm/iobroker.material/)

React and Material UI interface.

![Screenshot](img/screenshot1.png)

## Installation
**Important!**
This adapter cannot be installed directly from github. Only from npm.

## Usage
It is very important to know, that adapter shows only devices that added to some categories, like *rooms* or *function*.
Better if every device belongs to both categories. Because every device has a type and place.


## Supported types
### Switch
### Dimmer
### Media player
### Volume
### Group volume

## ToDO
* Cams (over extra Adapter)
* events (over extra Adapter)
* Main screen
* Charts
* Narrow menu
* Sort order of tiles
* vacuum cleaner
* show bar for sliders to indicate position
* support of quality codes
* configurable humidity ID and temperature ID for weather widget
* do not load at reconnection all objects, just subscribed states
* Show images / URL
* Do not close menu if clicked on group

## Credits
- Used icons from flaticon
- Volume knob from [here](https://codepen.io/blucube/pen/cudAz) By [Ed Hicks](https://twitter.com/blucube) - Inspired by a [dribbble shot](https://dribbble.com/shots/753124-Volume-Knob)  by [Ricardo Salazar](https://twitter.com/rickss)

## Changelog
### 0.9.7 (2018.07.30)
* (bluefox) Implemented the weather widget

### 0.9.4 (2018.07.26)
* (bluefox) Bug-fixes

### 0.9.3 (2018.07.25)
* (bluefox) Many changes

### 0.9.2 (2018.07.21)
* (bluefox) Update logic was implemented (only with web 2.4.1)

### 0.9.1 (2018.07.20)
* (bluefox) Volume control was implemented

### 0.8.9 (2018.07.17)
* (bluefox) React app

### 0.5.7 (2018.01.24)
* (bluefox) Ready for cloud services

### 0.5.6 (2017.10.11)
* (bluefox) fix undefined names
* (bluefox) fix detection of switches

### 0.5.3 (2017.08.11)
* (bluefox) fix dimmer

### 0.5.2 (2017.07.30)
* (bluefox) fix action icons

### 0.5.1
* (bluefox) edit of visibility

## License
CC-BY-NC

Copyright (c) 2017-2018 bluefox <dogafox@gmail.com>

Commercial use is not allowed.
