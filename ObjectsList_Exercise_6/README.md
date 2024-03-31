# Stepping Through All Objects in Model Space in ObjectARX Project

To step through all objects in model space in your ObjectARX project using Microsoft Visual Studio, follow these steps:

## Defining a Function to List Objects

1. Open your ObjectARX project.
2. Place the cursor after the line `#include "dbents.h"` and press Enter twice.
3. Add the code to define a function named `listObjects`.

## Modifying acrxEntryPoint Function

In the `acrxEntryPoint` function, add the following line:
   ```cpp
   acedRegCmds->addCommand(_T("AUCommands"), _T("ListObjects"), _T("ListObjects"), ACRX_CMD_MODAL, listObjects);

# Saving, Building, and Loading the Project

1. Save any changes made to the project.
2. Build the project to compile the code.
3. Load the `output.arx` file into AutoCAD.

## Listing Objects in AutoCAD

1. Add some objects to the current drawing, such as lines, circles, polylines, and so on.
2. At the Command prompt, type `listobjects` and press Enter.
3. Close the AutoCAD Text Window or collapse the Command Line window when done.

## Unloading the output.arx File

Unload the `AU2014.arx` file from AutoCAD.

Adjust paths and settings according to your specific environment.


This Markdown-formatted README section provides step-by-step instructions for stepping through all objects in model space in an ObjectARX project using Microsoft Visual Studio and testing it in AutoCAD.
