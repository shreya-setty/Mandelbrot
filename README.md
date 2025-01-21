# Mandelbrot Set Visualization

This project is a computer graphics application that visualizes the Mandelbrot set. The Mandelbrot set is a famous fractal, defined as the set of complex numbers \(c\) for which the sequence \(z_{n+1} = z_n^2 + c\) does not diverge when iterated from \(z_0 = 0\). It is renowned for its intricate, self-similar patterns and infinite complexity.

![6](https://github.com/user-attachments/assets/7716352f-4312-4a3a-9a6f-5f03b9fcc56f)

## Features

- **Interactive Visualization**: Explore the Mandelbrot set in real-time with zoom and pan capabilities.
- **Customizable Parameters**:
  - Adjust the maximum number of iterations for precision and detail.
  - Experiment with various color schemes to enhance visualization.
  - Modify the resolution for performance tuning.
- **Efficient Rendering**: Optimized algorithms for smooth and responsive exploration.
- **Cross-Platform Compatibility**: Runs on multiple operating systems, including Windows, macOS, and Linux.

![5](https://github.com/user-attachments/assets/3bf6e138-9c61-4be8-acaf-2b202d19178e)

## Technologies Used

- **Programming Language**: C++
- **Graphics Library**: OpenGL (or any other rendering library used, e.g., SDL, SFML)
- **IDE/Build Tools**: Specify the development environment and tools, such as Visual Studio, Code::Blocks, or Makefiles.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shreya-setty/Mandelbrot.git
   cd Mandelbrot
   ```

2. **Install Dependencies**:
   - On Ubuntu/Debian:
     ```bash
     sudo apt-get install libgl1-mesa-dev libglu1-mesa-dev
     ```
   - On Windows:
     - Install necessary OpenGL-related DLLs and configure them in your IDE.
   - On macOS:
     ```bash
     brew install glew
     ```

3. **Compile the Project**:
   ```bash
   g++ -o mandelbrot mandelbrot.cpp -lGL -lGLU -lglut
   ```
   Replace `mandelbrot.cpp` with your actual source file if it has a different name.

4. **Run the Program**:
   ```bash
   ./mandelbrot
   ```

## How to Use

1. **Launch the Application**:
   - Open a terminal or your IDE's debugger to execute the compiled program.

2. **Interactive Controls**:
   - **Zoom**: Use the mouse scroll wheel or assigned keys to zoom in and out of the fractal.
   - **Pan**: Click and drag with the mouse, or use arrow keys to navigate across the set.
   - **Adjust Iterations**: Press `+` or `-` keys to increase or decrease the number of iterations, controlling the level of detail.
   - **Change Color Schemes**: Press `C` (or another designated key) to cycle through predefined color palettes.

3. **Explore**:
   - Click on regions of interest to focus on specific patterns and observe the self-similarity and infinite complexity of the Mandelbrot set.

## Screenshots

_Add high-quality screenshots of the Mandelbrot set visualization here to demonstrate various zoom levels and color schemes._

## Customization

To tailor the application to your needs, you can modify the following parameters in the source code:

- **Maximum Iterations** (`MAX_ITERATIONS`): Determines the precision and depth of the fractal.
- **Color Scheme** (`COLOR_SCHEME`): Adjust or create new color gradients for unique visual effects.
- **Resolution**: Modify the rendering resolution for improved performance or detail.
- **Zoom Speed**: Fine-tune the zoom speed for smoother navigation.

## Challenges and Optimizations

- **Rendering Efficiency**: Optimized to minimize computation time while maintaining accuracy.
- **Precision Handling**: Implemented methods to prevent floating-point inaccuracies at extreme zoom levels.
- **Color Mapping**: Carefully designed to highlight the fractal's intricate details effectively.

## Contributions

Contributions are welcome! Here are ways you can contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.

Feel free to create issues for suggestions, feature requests, or bugs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the beauty of fractals and their mathematical significance.
- References and Resources:
  - [Wikipedia: Mandelbrot Set](https://en.wikipedia.org/wiki/Mandelbrot_set)
  - [OpenGL Documentation](https://www.opengl.org/documentation/)
  - Tutorials on fractals and computer graphics.

---

Thank you for exploring this project! Enjoy delving into the mesmerizing world of fractals! 🌌
