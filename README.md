cadquery-freecad-module
=======================
[![GitHub version](https://badge.fury.io/gh/jmwright%2Fcadquery-freecad-module.svg)](https://github.com/jmwright/cadquery-freecad-module/releases)
[![License](https://img.shields.io/badge/license-LGPL-lightgrey.svg)](https://github.com/jmwright/cadquery-freecad-module/blob/master/LICENSE)

A module-workbench combo that adds a CadQuery editor to FreeCAD. Please see the [wiki](https://github.com/jmwright/cadquery-freecad-module/wiki) for more detailed information on getting started.

![alt tag](https://cloud.githubusercontent.com/assets/1015439/7115894/b17536c0-e1ba-11e4-9316-ac66e4e706d9.png)

## Installation
**Requires FreeCAD 0.14 or newer**

Download the [latest released version](https://github.com/jmwright/cadquery-freecad-module/releases), extract the archive file, and copy the `CadQuery` directory to FreeCAD's `Mod` directory on your system. The module is implemented completely in Python so it should just work the next time you start FreeCAD. Some typical `Mod` directory locations are as follows.

### Linux
* ~/.FreeCAD/Mod <-- Best place to install under linux
* /usr/lib/freecad/Mod
* /usr/local/lib/freecad/Mod

If you are running Ubuntu Linux, be sure to run the following line in a terminal before using this module.
```
sudo apt-get install python-pyside.qtnetwork
```

### Windows
* C:\Program Files\FreeCAD 0.14\Mod
* C:\Program Files (x86)\FreeCAD 0.14\Mod

### Mac
* /Applications/FreeCAD.app/Contents/Mod
* /Applications/FreeCAD.app/Mod

## It's Installed, Now What?
For getting started information and troubleshooting steps, please see the [wiki](https://github.com/jmwright/cadquery-freecad-module/wiki)
