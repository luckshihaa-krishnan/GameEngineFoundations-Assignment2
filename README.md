# GameEngineFoundations-Assignment2

### What library did you use?
The libraries I used are:
  - using OpenTK.Windowing.Desktop
  - using OpenTK.Graphics.OpenGL
  - using OpenTK.Mathematics
  - using OpenTK.Windowing.Common

OpenTK.Windowing.Desktop is used to make sure that when the application runs, an OpenTK window opens to display the graphics. 

OpenTK.Graphics.OpenGL is used to make sure that 2D and 3D graphics are displayed in the OpenTK window.

OpenTK.Mathematics is used to handle all mathematical calculations in the application. This including using the dot and cross product and the movement of the objects.

OpenTK.Windowing.Common is used to manage the window.


### Which operations did you implement
The operations I implemented are:
  - Addition and Subtraction, using two vectors
  - Dot and Cross product, using two vectors
  - Normalization for a specific vector
  - Scale, Translation and Rotation matrix, for the shape
  - Quaternion to rotate the shape


### Example output from your test program
When the application runs, the output should be:
  1) Terminal opens which shows:
      - Vector 'a', 'b', and 'c'
      - Sum and difference of vector 'a' and 'b' using vector 'c', by using addition and subtraction
      - Product of vector 'a' and 'b' by using the Dot and Cross product
      - Normalization value using vector 'a'
  2) OpenTK Window opens which shows:
      - Purple color background
      - Yellow rectangle rotating on Y axis. It will rotate from big to small. 
