## 3D Viewer
School 21 programming school educational project.<br>

The 3D viewer program a robust platform for working  with 3D wireframe models. It offers essantial manipulation tools, a user-friendly interface, and additional customization options for an enriched user experience.<br>

<p align="center">
  <img src="gif/open_file.gif" alt="Open_file_presentation" width="600">
</p>

You can also move, zoom out, zoom in and rotate the model.<br>
The program is optimized to handle models with varying complexities, from 100 to 1,000,000 vertices, ensuring smooth performance without interface freezing.<br>

<p align="center">
  <img src="gif/move.gif" alt="Move_presentation" width="400">
  <img src="gif/rotate.gif" alt="Rotate_presentation" width="400">
</p>

In the lower right corner are the display settings. They are saved between sessions.

<p align="center">
  <img src="gif/scale_settings.gif" alt="Scale_settings_presentation" width="400">
  <img src="gif/color_settings.gif" alt="Color_settings_presentation" width="400">
</p>

<br>
<br>
## Installation
To install, you will need Qt version 6, cmake, make, and a GCC compiler.<br>
Navigate to the `src` directory and run the `make install` command.

## For developers
The project is developed following the MVP pattern on the Qt framework, in C++17 language .<br>
The render window uses the openGL library.<br>
All code related to the Model block is documented. To view the doxygen documentation, navigate to the "src" directory and run the "make dvi" command.<br>
