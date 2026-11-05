# 3D Building Material BOQ

A browser-based 3D building modeling and material quantity takeoff application designed to help users create building elements, visualize construction components, and estimate material quantities through an interactive 3D environment.

## Overview

**3D Building Material BOQ** combines 3D building modeling with material quantity calculation in one web application. Users can work with building elements in a 3D scene, manage construction components, assign materials, and generate quantity information to support preliminary construction estimation.

The project is built with JavaScript and Three.js, with a modular architecture that separates building models, geometry, materials, calculations, and user interface tools.

## Features

### 3D Modeling & Visualization
- Interactive 3D workspace with camera controls.
- Create and manage building elements.
- Visualize walls, floors, openings, and other building components.
- Transform and edit objects within the 3D scene.

### Building Components
- Wall creation and management.
- Door and window opening management.
- Floor and room detection.
- Building geometry and component handling.

### Material Management
- Material library for construction materials.
- Assign and customize materials for building elements.
- Texture loading, caching, and cropping tools.

### Quantity Takeoff & BOQ
- Calculate building component quantities.
- Estimate material quantities based on model geometry.
- Aggregate calculation results.
- Generate material quantity information for BOQ purposes.

### Project Management
- Save and load project data in JSON format.
- Undo and redo editing operations.
- Manage building components through modular tools.

## Technology Stack

| Technology | Purpose |
|---|---|
| JavaScript (ES Modules) | Application logic and modular architecture |
| Three.js | 3D rendering and visualization |
| HTML5 | Application structure |
| CSS3 | User interface and styling |
| JSON | Project data serialization |

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Vannachat/3D_Building_Material_BOQ.git
```

### 2. Open the Project

```bash
cd 3D_Building_Material_BOQ
```

### 3. Run a Local Web Server

Because the application uses JavaScript ES Modules, open it through a local web server rather than directly opening `index.html`.

For example, using Python:

```bash
python -m http.server 8000
```

### 4. Open in Your Browser

Visit:

```text
http://localhost:8000
```

Alternatively, use the **Live Server** extension in Visual Studio Code.

## Project Structure

```text
3D_Building_Material_BOQ/
│
├── index.html
├── script.js
├── style.css
│
├── src/
│   ├── app/              # Application initialization
│   ├── building/         # Building models and components
│   ├── boq/              # BOQ calculation logic
│   ├── calculation/      # Quantity calculation and aggregation
│   ├── core/             # Core utilities and event management
│   ├── geometry/         # Geometry generation
│   ├── history/          # Undo and redo functionality
│   ├── i18n/             # Internationalization
│   ├── interaction/      # User interaction systems
│   ├── landplot/         # Land plot geometry and detection
│   ├── materials/        # Material library and texture tools
│   ├── persistence/      # Project save and load
│   ├── scene/            # 3D scene rendering
│   └── ui/               # Building tools and user interface
│
├── tests/                # Core application tests
└── docs/                 # Technical documentation
```

## Live Demo

Try the application here:

**[3D Building Material BOQ – Live Demo](https://vannachat.github.io/3D_Building_Material_BOQ/)**

## Repository

**GitHub:** https://github.com/Vannachat/3D_Building_Material_BOQ

---

*This project was developed as an independent project to explore 3D building modeling, construction material management, and automated quantity takeoff using web technologies.*
