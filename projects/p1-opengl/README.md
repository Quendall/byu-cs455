### BYU CS 455
# Program 1 - OpenGL with Shaders or Houdini

## Option 1: OpenGL

The purpose of this project is to help you learn the basics of modern OpenGL. You will need to get OpenGL up and running, then draw a triangle (or some other object) to the screen.

The newest versions of OpenGL are all shader based, meaning that all objects are drawn based on shaders that are created for them. This form of graphics is less intuitive than early versions of OpenGL, but is much more suited for modern GPUs. However, there is a fair amount of overhead associated with getting OpenGL to run.

### Project Setup

There is an OpenGL package called "Glitter" that takes care of a lot of the overhead in getting an OpenGL program to run. Glitter packages up all of the libraries, helper code, etc. into one location to simplify running OpenGL. We have created a github repository that contains the Glitter code you will need for your program. It can be found here: https://github.com/NathanZabriskie/Glitter

In addition, there are step-by-step instructions on loading and using Glitter in your OpenGL code. You need to install Glitter (as instructed in that repository) then edit main.cpp to add your code.

*Note: If you are using MacOS, there is currently a glitch that you will need to fix. Go to https://github.com/Polytonic/Glitter/issues/37#issuecomment-361056655 for assistance in fixing this.*

### Requirements

There are two places in main.cpp where you will write your code. They are clearly marked in the file. You will first need to set up your vertex array, then you will need to render your object.

After adding your code, you will need to compile and run the program. For program 1, we supply the shader for you so you don't have to worry about it.

### Submission

You should only have to submit your `main.cpp` file. If you have any other special requirements so it runs correctly, include that in the submission notes.

## Option 2: Houdini

A second option is to become familiar with and use Houdini. Houdini is a software package that allows you to do modeling, animation, lighting, and effects. If you have used Houdini, this option will probably not be all that beneficial to you.
For this assignment you will create a mountain. After you have created it, you will need to play around with Houdini to make it look good, color or texture it, add any frills to it, and render it out. 

Creating a simple mountain takes about 2 minutes in Houdini, so you will be expected to put in additional time enhancing it and making it look really good.
Student licenses of Houdini are available free of charge to BYU students. If you select this option, I will need to get your BYU email address to register you for the software. You will then get an email from Houdini with a link to install the software.

In order to run Houdini reasonably, you will need a decent amount of RAM and GPU. If your home machine or laptop does not meet these requirements, you are welcome to use the department machines.

*Note: Kendall (the TA) does not have experience with Houdini, so he will not be able to help you if you choose this option. You will need to find help online or from your classmates if you run into any issues.*