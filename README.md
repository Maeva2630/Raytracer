# Raytracer

> **Epitech Tek2 — Object-Oriented Programming & Computer Graphics (C++20)**  
> A high-performance, extensible, plugin-based Raytracing engine built in **C++20** with dynamic loading of primitives, lights, materials, skies, and renderers.

---

## Key Features

- **Plugin Architecture**: Dynamically loadable shared libraries (`.so`) for shapes, lights, materials, skies, and renderers.
- **Primitives**: Sphere, Plane, Cylinder, Infinite Cylinder, Cone, Limited Cone, Torus, Box, Triangle, 3D Mesh (`.obj`), Tanglecube, and Fractals.
- **Materials**: Flat, Phong shading, Metallic reflections, Transparency / Refraction, and Emissive Light materials.
- **Lighting**: Ambient, Directional, Point, and Spot lights with shadows.
- **Skyboxes**: Atmospheric sky, Galaxy sky, and Empty sky.
- **Renderers & Live Preview**: Default & Fast renderers, interactive **SFML live display**, automatic **file watcher** for hot-reloading scenes, and network rendering support.
- **Scene Configuration**: Declarative `.scene` files parsed with `libconfig++`.

---

## Getting Started

### Prerequisites
- **C++20 Compiler**: GCC 10+ or Clang 10+
- **CMake**: Version 3.15+
- **Libraries**: `libconfig++`, `SFML` (for live display)

### Build
```bash
mkdir -p build && cmake -B build -S . && cmake --build build
```

### Run a Scene
```bash
./raytracer scenes/showcase/primitives/sphere.scene
```

---

## Documentation

- **Plugin Development Guides**:
  - [Adding a Light](./docs/lights.md)
  - [Adding a Shape](./docs/shapes.md)
  - [Adding a Material](./docs/materials.md)
- **Scene Configuration**:
  - [Scene Setup](./docs/scenes.md)

---

## Credits

Built as an Epitech Tek2 OOP project by **Maëva Arroniz** ([@Maeva2630](https://github.com/Maeva2630)), **Alban Lembrez** ([@Saitamadupauvre](https://github.com/Saitamadupauvre)), **Teddy Bertrand** ([@TeddyBertrand](https://github.com/TeddyBertrand)), and **Amayyas**.
