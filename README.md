# 3d-files
My collection of sliced print files for my Robo C2 3D printer

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
