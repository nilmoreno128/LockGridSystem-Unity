# Lock Grid System

A Unity tool designed to automatically snap objects to a grid in the editor, ensuring consistent positioning and alignment in your scenes. This asset is particularly useful for games or applications that require precise object placement, like tile-based levels.

## Features

- **Grid Snapping**: Automatically snaps objects to a grid of a specified size.
- **Toggleable System**: Easily enable or disable grid snapping via a single variable.
- **Customizable Grid Size**: Define the size of the grid to match your project's requirements.
- **Editor Integration**: Works seamlessly in edit mode, keeping your scene organized during development.

## Installation

1. Download the [`LockGrid.unitypackage`](LockGrid.unitypackage) file from this repository.
2. Open your Unity project and go to **Assets > Import Package > Custom Package**.
3. Select the `LockGrid.unitypackage` file and click **Import**.

## How to Use

1. Add the `LockGrid` script to any GameObject you want to snap to the grid.
2. Configure the settings:
   - **Enable Grid**: Toggle this option in the Inspector to turn grid snapping on or off.
   - **Tile Size**: Specify the size of the grid tiles.
3. The GameObject's position will automatically snap to the nearest grid point in edit mode.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
