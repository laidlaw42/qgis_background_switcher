# Background Switcher Plugin for QGIS

## Description:

Similar to the toggler plugin, this uses a dropdown menu instead of a toggle button.
The Background Switcher plugin for QGIS allows users to quickly switch the background color of the map canvas using a dropdown menu in the toolbar. This plugin simplifies the process of changing the background color to predefined options such as black, white, or grey.

## Features:

- Adds a dropdown menu to the QGIS toolbar for selecting background colors.
- Provides options to switch between predefined background colors: black, white, and grey.

## Implementation Details:

- The plugin is implemented using the QGIS plugin framework.
- PyQt5 is used for creating GUI elements and handling user interactions.
- The plugin utilizes a QComboBox widget to display the dropdown menu for selecting background colors.
- Predefined color options (black, white, grey) are added to the dropdown menu.
- Canvas background color is updated dynamically based on the selected option in the dropdown menu.
- The plugin includes methods for initializing the GUI, handling user interactions, and managing plugin lifecycle.

## Usage:

1. Download a zip of this repo.
2. In QGIS, go to Plugins > Manage and Install Plugins... > Install from zip
2. Activate the plugin from the Plugins menu.
3. A dropdown menu labeled "Background Switcher" will appear in the toolbar.
4. Select a background color from the dropdown menu to update the map canvas.

## Requirements:

- QGIS 3.x
- PyQt5

## License:

- GNU General Public License version 2 or later
