# Live Tile

A simple, client-side tool for visualizing seamless tiles in real-time.

![Screenshot of Live Tile](TODO)

## Features

*   **Live Reload:** Automatically updates the tiled image when the source file is saved.
*   **Drag and Drop:** Simply drag your image file onto the grid to get started.
*   **Adjustable Grid Size:** Change the grid dimensions using a dropdown, mouse wheel, keyboard shortcuts, or pinch gestures.
*   **Grid Overlay:** Toggle a grid overlay to better visualize the tile edges.
*   **Cross-platform:** Works in any modern browser that supports the File System Access API (Chrome, Edge, Opera).

## How to Use

1.  **Open the page:** For the best experience (including live reload), it's recommended to run a local web server. A simple way to do this is to navigate to the project directory in your terminal and run:
    ```bash
    python -m http.server
    ```
    Then, open your browser and go to `http://localhost:8000`.

    Alternatively, you can simply open the `index.html` file directly in your browser, but the live reload feature may not work due to browser security restrictions.

2.  **Load an image:**
    *   Drag and drop your image file onto the grid.
    *   Or, click the "Choose file" button to select an image.

3.  **Adjust the grid:**
    *   Use the dropdown menu in the top bar.
    *   Use your mouse wheel over the grid.
    *   Use the `+` and `-` keys, or `Home` and `End` keys.
    *   Pinch to zoom on a touch device.

4.  **Toggle the grid overlay:**
    *   Click the grid icon in the top bar.
    *   Press the `G` key.

5.  **Live edit:**
    *   Open your image file in your favorite editor (e.g., Photoshop, Aseprite).
    *   Make your changes and save the file.
    *   The image in Live Tile will update automatically.

## Development

This project is a single, self-contained `index.html` file. There are no external dependencies or build steps.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
