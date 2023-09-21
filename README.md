```
██╗    ██╗ ██████╗ ██╗  ██╗███████╗██╗         ██╗    ██╗███████╗██████╗ 
██║    ██║██╔═══██╗╚██╗██╔╝██╔════╝██║         ██║    ██║██╔════╝██╔══██╗
██║ █╗ ██║██║   ██║ ╚███╔╝ █████╗  ██║         ██║ █╗ ██║█████╗  ██████╔╝
██║███╗██║██║   ██║ ██╔██╗ ██╔══╝  ██║         ██║███╗██║██╔══╝  ██╔══██╗
╚███╔███╔╝╚██████╔╝██╔╝ ██╗███████╗███████╗    ╚███╔███╔╝███████╗██████╔╝
 ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═╝╚══════╝╚══════╝     ╚══╝╚══╝ ╚══════╝╚═════╝ 
```
https://woxel.xyz - https://github.com/woxels/Woxel

Mouse locks when you click on the window, press ESCAPE to unlock the mouse.

Your state is automatically saved.

#### Movement:
* W,A,S,D / UP,DOWN,LEFT,RIGHT = Move around based on relative orientation to X and Y.
* SPACE / L-SHIFT // R-CTRL / R-SHIFT = Move up and down relative Z.
* F = Toggle player fast speed on and off.
* 1-7 = Change move speed for selected fast state.
* P = Toggle pitch lock.

#### Interaction:
* Left Click / U = Place node.
* Right Click / O = Delete node.
* I,J,K,L = Look/View pan.
* Q / Z / Middle Click = Clone color of pointed node.
* E = Replace color of pointed node.
* R = Toggle mirror brush.
* V = Places voxel at current position.
* X + C / Slash + Quote = Scroll color of pointed node.

#### Settings:
* F1 = Resets environment state back to default.
* F2 = Toggle HUD visibility.
* F7 = Erases all voxels from the canvas and resets state.
* F8 = Export voxels as TEXT to file download.
* F9 = Export voxels as PLY ASCII to file download.

When **exporting as ply** you will want to `merge vertices by distance` in Blender
or `Cleaning and Repairing > Merge Close Vertices` in MeshLab.

The **mouse sensitivity** is changed by supplying it as the only url parameter as so: https://woxel.xyz?0.01 will set the mouse sensitivity to 0.01.

**To set colors in the palette** you must specify the color id (1-32) and then then HEX color as 6 characters without the #, e.g; https://woxel.xyz?1&00FFFF will set color 1 in the palette to #00FFFF (cyan).

#### Menu Palette:
* **Middle Mouse** clicking the color palette in the menu will copy the hex of the pointed color to the clipboard.
* **Right Mouse** clicking the color palette in the menu will randomize the color pointed to in the palette.
* Default Color Palette: https://lospec.com/palette-list/resurrect-32
