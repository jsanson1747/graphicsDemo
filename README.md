# 2D graphicsDemo

This assignment focuses on demonstrating graphics primitives. I utilized C++ for my language of choice because I wanted to be able to compile it down to an executable file for ease of running. To demonstrate these primitives, I decided to folow an algorithm for rotating a triangle recursively while changing size and color. The program launches into a text-based manu system in the console where it prompts the user to specify some parameters for the recursive function. Once all the parameters have been obtained, the code launches the graphics library and performs the recursive algorithm. Credit goes to the lovely people at MIT for outlining this particular algorithm that I translated into C++ with a few minor differences.

Recursive Drawing Algorithm from MIT ==> http://bricault.mit.edu/recursive-drawing

## Running the Program
In order to run this program, ensure that the graphicsDemo.exe is in the same directory as the SDL2.dll libraries. Without this, the executable won't have access to the necessary graphics library. Running the program is a simple as running the executable. 

The source code is availaible within the zip file. I compressed my entire working directory so it contains the SDL2 library, my source code, and some configuration files I used for compiling this project in Visual Studio Code.

## Program Structure
Since I utilized C++, I took advantage of some Object Oriented Design for encapsuating plotting points and drawing lines to the graphics context. My program had the following struture. 

![graphicsDemo drawio](https://user-images.githubusercontent.com/107002749/193477513-2c441902-138d-4799-bed3-31c2b80be7ad.png)

I utilized the SDL2 graphics library for C++ as my main graphics driver. 
