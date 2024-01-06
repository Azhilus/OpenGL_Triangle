# OpenGL Colored Triangle

This simple C++ program utilizes GLFW and GLAD to create an OpenGL window and render a colored triangle. The triangle is defined by vertex and fragment shaders, and the program provides a basic structure for setting up OpenGL, compiling shaders, and rendering graphics.

<img src="https://github.com/Azhilus/OpenGL_Triangle/assets/66466976/c98d6aaf-286b-4b17-b7c8-f8c87c104b0f" width="600">


## Prerequisites
- [GLFW](https://www.glfw.org/) library
- [GLAD](https://glad.dav1d.de/) loader

## Building and Running
1. Make sure you have GLFW and GLAD installed.
2. Compile the program using your preferred C++ compiler. For example, using g++:

   ```bash
   g++ -o main main.cpp -lglfw -ldl
   ```

3. Run the executable:

   ```bash
   ./main
   ```

## Controls
- Press `ESC` to close the window.

## Code Overview
- The program initializes GLFW and sets up an OpenGL 3.3 Core Profile window.
- Vertex and fragment shaders define the geometry and color of the triangle.
- Vertex data and buffers are created, and shaders are compiled and linked into a shader program.
- The main rendering loop clears the screen, uses the shader program, and draws the triangle.
- Cleanup is performed at the end of the program.

Feel free to modify and extend this code to experiment with OpenGL graphics programming.
