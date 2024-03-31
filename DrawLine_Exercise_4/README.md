# Adding a Line to Model Space in ObjectARX Project

To add a line to model space in your ObjectARX project using Microsoft Visual Studio, follow these steps:

## Creating a New Graphical Object

1. Open your ObjectARX project.
2. Place the cursor after the line `#include "dbents.h"` and press Enter twice.
3. Add the line of code to define a function named `addLinee`.

## Saving and Building the Project

1. Save the changes to the ObjectARX project.
2. Build the ObjectARX project and load the `AU2014.arx` file into AutoCAD.
   - Unload the `drawLineOfFixedLength.arx.arx` file from AutoCAD or close and restart AutoCAD before building the project.

## Adding a Line and Checking in AutoCAD

1. At the Command prompt, type `addlinee` and press Enter.
2. Zoom to the extents of the drawing to see the whole.
3. In the drawing area, select the line. Right-click and choose **Properties**.
4. Close the Properties palette and unload the `drawLineOfFixedLength.arx.arx` file from AutoCAD.
