# 3D Visualizer

This project is a 3D visualizer that allows users to interact with a 3D model of a rib slab. The visualizer utilizes Three.js for rendering and provides functionality for visual clipping and simulated falling of the cut piece.

## Project Structure

```
3d-visualizer
├── assets
│   ├── Rib_Slab_0407173318_texture.mtl  # Material definitions for the 3D model
│   └── Rib_Slab_0407173318_texture.obj  # 3D model file in OBJ format
├── src
│   └── index.html                        # Main HTML document for the visualizer
├── .gitignore                            # Git ignore file
└── README.md                             # Project documentation
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd 3d-visualizer
   ```

2. **Open the Project**
   Open `src/index.html` in a web browser to view the 3D visualizer.

## Usage

- Click the "Activar Corte Visual" button to enable visual clipping.
- Drag the mouse over the model to define the clipping plane.
- Release the mouse button to simulate the falling of the cut piece.

## Dependencies

This project uses [Three.js](https://threejs.org/) for 3D rendering. Ensure you have an internet connection to load the library from the CDN specified in `index.html`.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.