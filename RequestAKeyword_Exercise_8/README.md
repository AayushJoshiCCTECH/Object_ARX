# Select Objects and Request a Keyword

This exercise demonstrates how to use the `acedSSGet` and `acedGetKword` functions to select objects and request a color to apply to the selected objects.

## Instructions

1. In Microsoft Visual Studio, open the ObjectARX project.

2. Place the cursor after the line `#include "dbents.h"` in the source code file and press Enter twice.

3. Define the `changeColor` function by typing the following code:

```cpp
acedRegCmds->addCommand(_T("AUCommands"), _T("ChangeColor"), _T("ChangeColor"), ACRX_CMD_MODAL | ACRX_CMD_USEPICKSET, changeColor);
```

1. **Save, Build, and Load the ARX File into AutoCAD:**
   - Save any changes made to the project.
   - Build the project to compile the code.
   - Load the `output.arx` file into AutoCAD.

2. **Change Color of Selected Objects:**
   - At the Command prompt, type `changecolor` and press Enter.
   - In the drawing area, select objects in the drawing and press Enter.
   - At the `Enter a color [Red/Yellow/Green/Bylayer] :` prompt, type `r` and press Enter.

3. **Repeat the Process:**
   - In the drawing area, select objects again.
   - At the Command prompt, type `changecolor` and press Enter.
   - At the `Enter a color [Red/Yellow/Green/Bylayer] :` prompt, type `g` and press Enter.

4. **Unload the ARX File from AutoCAD:**
   - Unload the `output.arx` file from AutoCAD.

Adjust paths and settings according to your specific environment.
