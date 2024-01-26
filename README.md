# Project3-RotatingCube
## ASCII 3D Cube Animation
- This program creates an ASCII art animation of three rotating cubes using C programming language. The animation is displayed in the console window.

## How to Run
1. Clone the repository or download the source code.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the source code.
4. Compile the code using a C compiler (e.g., gcc).
   -     gcc -o ascii_cube_animation ascii_cube_animation.c -lm
5. Run the compiled executable
   -     ./ascii_cube_animation
## Controls
   - The animation will run automatically. To exit the program, press Ctrl+C.
## Code Explanation
- The code defines a 3D space and calculates the positions of the cubes in that space. It utilizes ASCII characters to represent surfaces and creates a 3D effect by adjusting the characters based on the distance from the camera.
- The animation consists of three cubes with different sizes and positions. The cubes rotate continuously around the X, Y, and Z axes.
## Customization
- You can customize the animation by adjusting the following variables in the code:
- cubeWidth: Controls the size of the cubes.
- incrementSpeed: Controls the step size for cube position calculation.
- backgroundASCIICode: ASCII code representing the background character.
- distanceFromCam: Distance of the camera from the cubes.
- K1: Adjusts the perspective effect.
- usleep: Adjust the sleep duration for controlling animation speed.

## Impact of the Code:
This code has been a valuable educational resource for me. It provided a hands-on opportunity to delve into basic 3D graphics concepts and understand how to render simple shapes in a console environment using ASCII characters.
The visual impact of the animation is noteworthy. Witnessing the representation of rotating cubes using ASCII characters offered a practical understanding of how geometric shapes can be visually manipulated in a 3D space.
Through this code, I gained insights into fundamental graphics concepts. The mathematical calculations involved in transforming 3D coordinates to 2D screen space, including rotations around different axes and perspective projection, were particularly illuminating.
The code's handling of platform-specific differences, especially in timing functions between Windows and Unix-like systems, broadened my understanding of cross-platform compatibility considerations in programming.
## What I Learned:
This coding experience deepened my understanding of 3D graphics mathematics. I learned to translate abstract concepts into tangible visual representations, a crucial skill in graphics programming.
The utilization of ASCII characters for graphics rendering was an eye-opener. I gained insights into the early methods of computer graphics and appreciated how simple characters could create visually appealing animations.
This project enhanced my C programming skills. From utilizing standard libraries to implementing platform-specific code and managing memory, the code structure and practices provided a holistic learning experience.
Animating the cubes introduced me to animation techniques. I learned how to create a continuous animation loop and control the animation speed through time delays, adding a dynamic aspect to my programming skills.
Lastly, the code's modularity and clear commenting helped me understand the importance of code structure. It emphasized the significance of writing clean and documented code for better comprehension and maintainability.
In summary, this coding experience not only introduced me to the fascinating world of 3D graphics but also honed my programming skills, providing a foundation for further exploration in graphics programming or related fields.

