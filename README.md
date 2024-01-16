# Multiple Windows 3D Example with Three.js

This web application demonstrates a 3D scene using the Three.js library, featuring support for multiple windows. Users can resize the windows, and their positions are synchronized across different browser windows or tabs.

## Getting Started

To run the application:

1. Clone the repository.
2. Open the `index.html` file in a web browser.

The application utilizes the Three.js library, and the necessary script is included in the HTML file.

## How It Works

The project consists of two main files:

### main.js

This file contains the primary logic for setting up the 3D scene, managing windows, and rendering cubes based on window positions.

### WindowManager.js

The `WindowManager.js` file defines the `WindowManager` class, which handles window management, synchronization, and storage using `localStorage`.

## WindowManager Class

The `WindowManager` class is responsible for:

- Initializing windows and storing their configurations.
- Detecting changes in window positions and sizes.
- Updating the window list in `localStorage`.
- Providing callbacks for window shape changes and general window changes.

## Usage

1. Open the `index.html` file in a web browser.
2. Interact with the application by resizing and moving windows.
3. Changes to window configurations are synchronized across different windows or tabs.

Feel free to explore the 3D scene and experiment with window interactions!
