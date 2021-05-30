# TimbaProject

This project was created with OpenGL Glut c++.

Installation process to open project in Visual Studio:

Go to Tools -> Get Tools and features

Install Desktop development with C++
Check if Windows 10 SDK (10.0.19041.0) is already installed.

And thatis all.

To open the .exe, you must need to have installed MSVC v142 VS 2019 C++ in your computer.

The purpose of this repo is to deliver the appropriate functionalities 
for the correct functioning of the test delivered by timba games, 
for the application of a video game developer.

To be honest, I am not familiar with c ++, but I found that using opengl together with the glut library, 
was the easiest way to carry out the challenge, it has 4 different classes, where I read the different 
files with their corresponding information, and then inherit them to the .cpp class where I do the necessary 
functions for the correct operation of the project.

In the header files, you can find 2 methods, the first "readFile", 
fulfills the function of reading the .txt, then filling a string vector with 
the information of each line, and then filling a float vector, with the numeric values, 
substringing each string line.

The second function "render", fulfills the function of rendering the object and also, 
checking the animation to be shown on the screen.

The .cpp file corresponds to the master class, where it performs all the necessary 
functions for the correct operation of the application, much of it is documented, so that it is easy to read.

![Cheat Sheet](Cheatsheet.PNG)
