I've uploaded a patch for v1.0 (v1.0a) that fixes a few bugs and adds a few minor features. Here's some changelog stuff:

    + Added functionality to the 'New Map' button on the wad manager window
    * Sometimes the map/grid lists wouldn't update correctly (casing them to disappear at certain times)
    * PNG files missing an alpha channel wouldn't load correctly
    * Starting 3d mode with no map open would crash
    + Added option to invert the mouse Y axis in 3d mode
    + Gravity in 3d mode is now toggleable
    ~ A message is now shown if a hexen format map is loaded when a non-hexen format game is selected
    * Textures weren't reloading properly (I wasn't clearing the PNAMES data)
