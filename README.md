# OpenGL

[![C++](https://img.shields.io/badge/language-C%2B%2B-blue)](#)  
[![OpenGL](https://img.shields.io/badge/graphics-OpenGL-green)](#)

A fun exploratory project using **OpenGL**, C++, and GLSL shaders to render graphics, experiment with lighting, textures, camera controls, and more.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Dependencies](#dependencies)  
- [Getting Started / Build Instructions](#getting-started--build-instructions)  

---

## About

This project is a hands-on playground to learn and experiment with OpenGL rendering techniques: shaders, meshes, textures, camera movement, etc. It serves as a foundation for more ambitious graphics projects (games, simulations, visualizations).

---

## Features

- Shader management (vertex, fragment shaders)  
- Mesh / geometry loading / manipulation  
- Texture loading and mapping  
- Camera controls (first-person / free camera)  
- Basic lighting models  
- Window & context handling  

---

## Project Structure

OpenGL-Fun-Project/
├── Header Files/
├── Shaders/
├── Textures/
├── Camera.cpp
├── Mesh.cpp
├── Shader.cpp
├── Texture.cpp
├── Window.cpp
├── main.cpp
└── README.md


- **Header Files/** — custom header files (e.g. class declarations).  
- **Shaders/** — GLSL shader source files (vertex, fragment).  
- **Textures/** — image files used as textures in rendering.  
- `.cpp` files — implementation of rendering pipeline, camera, mesh handling, etc.  
- `main.cpp` — program entry, sets up window, OpenGL context, render loop.

---

## Dependencies

You’ll need the following installed / configured on your system:

- A C++ compiler supporting C++11 or newer  
- OpenGL (core profile)  
- GLFW (for window & input)  
- GLAD or GLEW (for OpenGL function loading)  
- stb_image (for texture loading)  
- Any image library / loader (if not included)  

> **Note:** Ensure your GPU drivers support the required OpenGL version.

---

## Getting Started / Build Instructions

Here's how you can build and run the project locally:

1. Clone the repository:  
   ```sh
   git clone https://github.com/Pavandeepsingh983/OpenGL-Fun-Project.git
   cd OpenGL-Fun-Project
