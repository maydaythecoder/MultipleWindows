# Multiple Windows 3D Example with Three.js

This project is a web application that demonstrates a 3D scene using Three.js with support for multiple windows. The windows can be resized, and their positions are synchronized across different browser windows or tabs.

## Getting Started

To run the application, simply open the `index.html` file in a web browser. The application uses Three.js library, and the necessary script is included in the HTML file.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>3D Example using Three.js and Multiple Windows</title>
    <script type="text/javascript" src="three.r124.min.js"></script>
    <style type="text/css">
        *
        {
            margin: 0;
            padding: 0;
        }
    </style>
</head>
<body>
    <script type="module" src="main.js"></script>
</body>
</html>

How It Works
The project consists of two main files:

main.js: This file contains the main logic for setting up the 3D scene, managing windows, and rendering cubes based on window positions.

WindowManager.js: This file defines the WindowManager class, which handles window management, synchronization, and storage using the localStorage.

WindowManager Class
The WindowManager class is responsible for:

Initializing windows and storing their configurations.
Detecting changes in window positions and sizes.
Updating the window list in localStorage.
Providing callbacks for window shape changes and general window changes.
Usage
Open the index.html file in a web browser.
Interact with the application by resizing and moving windows.
Changes to window configurations are synchronized across different windows or tabs.
