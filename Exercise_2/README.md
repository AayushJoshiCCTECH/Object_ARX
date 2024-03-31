# Compiling and Loading the AU2014 ObjectARX Project

This exercise explains how to compile the AU2014 ObjectARX project and then load it into AutoCAD.

## Compiling the Project
1. In Microsoft Visual Studio, on the menu bar, click **Build** ➔ **Build Solution**.
   - You should see a message indicating that the build succeeded: `1>Build succeeded`.

## Loading the Project into AutoCAD
1. Start AutoCAD.
2. In AutoCAD, on the ribbon, click **Manage** tab ➔ **Applications** panel ➔ **Load Application**.
3. In the Load/Unload Applications dialog box, browse to the location of the compiled ARX file.
   - Select **AU2014.arx** and click **Load**.
4. In the **File Loading - Security Concern** message box, click **Load**.
5. Click **Close**.
6. Press **F2** to display the AutoCAD Text Window or expand the Command Line window. You should see the following messages:

- The message 'Loading AU2014 project...' is displayed using the `acutPrintf` method in the `acrxEntryPoint` function when `kInitAppMsg` is handled.

## Unloading the Project from AutoCAD
1. In AutoCAD, on the ribbon, click **Manage** tab ➔ **Applications** panel ➔ **Load Application**.
2. In the Load/Unload Applications dialog box, under the **Loaded Applications** tab, select **AU2014.arx** and click **Unload**.
3. Click **Close**.
4. Press **F2** to display the AutoCAD Text Window or expand the Command Line window. You should see the following messages:

- The message 'Unloading AU2014 project...' is displayed using the `acutPrintf` method in the `acrxEntryPoint` function when `kUnloadAppMsg` is handled.