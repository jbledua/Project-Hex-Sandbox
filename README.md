# Project-Hex-Sandbox

Project-Hex-Sandbox is a Python-based experimental environment for researching tilemap representations and image-to-tilemap conversion techniques. It serves as a sandbox and prototyping space for the broader **Project-Hex** game project.

The primary focus is on evaluating different grid systems and computer vision workflows prior to implementation in a game engine such as Godot.

---

## Objectives

This project has two core research objectives:

### 1. Tile Structure Efficiency
Evaluate how efficiently different tile grid structures represent basic geometric shapes while minimizing tile count and distortion:
- Hexagonal grids
- Isometric grids
- Orthogonal (square) grids

Test cases include lines, circles, angles, and simple composite shapes.

### 2. Image-to-Tilemap Conversion
Explore the feasibility and complexity of using computer vision techniques (e.g. OpenCV) to convert 2D top-down map images into structured tilemaps suitable for use in games.

This includes:
- Edge and feature detection
- Grid alignment and snapping
- Error tolerance and approximation trade-offs

---

## Tech Stack

- **Python 3**
- **Jupyter Notebooks** (exploration and visualization)
- **OpenCV** (image processing and computer vision)
- **NumPy / Matplotlib** (numerical analysis and visualization)

---

## Repository Structure

```text
Project-Hex-Sandbox/
├── notebooks/          # Jupyter notebooks for experiments and analysis
├── src/                # Reusable modules and helper code
├── data/               # Sample images and test inputs
├── .venv/              # Local Python virtual environment (gitignored)
├── requirements.txt    # Python dependencies
└── README.md
