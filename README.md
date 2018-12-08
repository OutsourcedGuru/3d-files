# 3d-files
My collection of sliced print files for my Robo C2 3D printer. They're usually sliced without rafts using 190°C for PLA and relative extrusion. I try to avoid supports if I can.

## Overview
Some OctoPrint users have asked for a method of storing their sliced files in a repository and then pulling down the latest copies to each of their production printers.

| Local git-controlled folder on workstation |
| --- |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⬇ `git add .` + `git commit` +  `git push`

| github repository |
| --- |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⬇ `git pull` (as implemented in this plugin)

| OctoPrint |
| --- |

## Suggested Folder Structure Indicating Materials
* /
  * PLA
      * microSD-clip.gcode
  * CF-PLA

## Alternate File-naming Strategy to Indicate Materials
* microSD-clip_PLA.gcode
* microSD-clip_CF-PLA.gcode

## Content Description
* `5milCamRing`: A cam ring cord tensioner for 4mm paracord, useful for securing a tent, for example. [30mm OD, accepts 4mm paracord, 6mm thickness, 8mm wide; no adhesion or supports, 100% infill]
* `Braille_a-z`: A test print of the letters A through Z in braille on a 100mm x 100mm square. [100mm x 100mm x 4mm; no adhesion or supports]
* `BatteryTool`: A small pry tool for removing AA/AAA batteries from a compartment as mounted into a tight space.
* `microSD-clip`: A small clip to temporarily hold a microSD card, suitable for positioning it back into place inside the bottom of a 3D printer. [no adhesion or supports, 100% infill]

![5milcamring](https://user-images.githubusercontent.com/15971213/49690366-8d9a7e80-fae4-11e8-91d1-99158f493822.png)

![braille_a-z](https://user-images.githubusercontent.com/15971213/49690452-30073180-fae6-11e8-90c1-4b3546857fd9.png)

![batterytool](https://user-images.githubusercontent.com/15971213/49690387-10bbd480-fae5-11e8-8c2d-ad458649a041.png)

![microsd-clip](https://user-images.githubusercontent.com/15971213/49690480-8ffdd800-fae6-11e8-82d2-de429e49c1ff.png)
