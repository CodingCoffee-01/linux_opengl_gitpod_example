//  CodingCoffee  OpenGL Gitpod Template more courses: www.codingcoffee.org 

 g++ triangle.cpp -lglut -lGL -o a.out 

//  glfw windows init and triangle Examples
g++ glfw_windows.cpp glad.c -o a.out -lglfw -lGL -lm -lXrandr -lXi -lX11 -lXxf86vm -lpthread -ldl -lXinerama -lXcursor

g++ -pthread -o a.out test_glfw_triangle.cpp glad.c -lglfw -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl

g++ -pthread -o a.out test_glfw.cpp -lglfw -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl
 
g++ glut_texture_ex1.cpp   -lglut -lGL -lGLU -o a.out

// Demo_CS_520 from : http://cse.csusb.edu/tongyu/courses/cs520/notes/

other OpenGL tutorial refs: 
1. https://github.com/opengl-tutorials/ogl
2. https://github.com/JoeyDeVries/LearnOpenGL
3. https://github.com/Overv/Open.GL
4. http://www.opengl-tutorial.org/download/
5. https://www.glprogramming.com/red/