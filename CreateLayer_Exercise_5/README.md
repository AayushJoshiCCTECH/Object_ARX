# Creating a New Layer in ObjectARX Project

To create a new layer in your ObjectARX project using Microsoft Visual Studio, follow these steps:

## Defining a Function to Create a Layer

1. Open your ObjectARX project.
2. Place the cursor after the line `#include "dbents.h"` and press Enter twice.
3. Add the code to define a function named `makeLayer`.

## Modifying acrxEntryPoint Function

In the `acrxEntryPoint` function, call the command to create the layer.

## Saving and Building the Project

1. Save the changes to the ObjectARX project.
2. Build the ObjectARX project and load the `AU2014.arx` file into AutoCAD.

## Creating a New Layer in AutoCAD

1. At the Command prompt, type `makerlayer` and press Enter.
2. From the ribbon, on the **Home** tab ➔ **Layers** panel, click the Layer drop-down list. The new layer named `OBJ` should now be listed.
   - The `OBJ` layer should be assigned the color Cyan.

## Unloading the AU2014.arx File

Unload the `AU2014.arx` file from AutoCAD.

Adjust paths and settings according to your specific environment.
