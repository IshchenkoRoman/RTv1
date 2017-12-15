# RTv1
## Intoduction
For once, the topic is related to the foreword. To succeed, you must fail. That’s why
you will start with some sort of proof-of-concept on the theory of *Raytracing*. It’s the
objective of **RTv1**: to get familiar with Ray-Tracing, geometric elements that you will
need to manipulate, the description of the scene... You will therefore succeed or fail this
project, with the end goal to do it again later bigger, better, more beautiful with all sorts
of additional features (it will be the *RT*, do not start *RT* if you did not do **RTv1**, it would
not be reasonable.)

## Objectives
When it comes to render 3 dimensions computer generated images there is 2 possible
approaches: “rasterization”, which is used by almost all graphic engines because of it’s
efficiency and “ray tracing.” The ray tracing method is more extensive and as a result
not adapted to real time but it produces a high degree of visual realism.

Before you can even begin to produce such high quality graphics, you must master
the basics: **RTv1** is your first ray tracer coded in C, normed, humble but functionnal.

At least you’ll then be able to show off nice looking pictures to justify the amount of
hours you’re spending at school instead of spending time with your special person :-).

## General Instructions
 1.  The executable file named RTv1.
 2.  Makefile must compile the project and must contain the usual rules. It does not recompile and re-link the program unless necessary.
 3.  This project use the **miniLibX**. Either in the version that is available on the system, or from its sources.
 4.  This project use the following functions:
     - 1) open, read, write, close
     - 2) malloc, free
     - 3) exit
     - 4) functions defined in the math library (-lm and man 3 math)
     - 5) functions defined in the **miniLibX** library.
     
 ## Mandatory part
1. Implement the Ray-Tracing method to create a computer generated image.
2. 4 simple geometric objects as a base (not composed): plane, sphere, cylinder and cone.
3. Program able to apply translation and rotation transformation to
objects before displaying them. For example a sphere declared at (0, 0, 0) must
be able to successfully translate to (42, 42, 42).
4. Smallest light management : different brightness, shadows.

 ## Bonus part
 
 -  [X] Multi-spots.
 -  [X] Shine effect.
 
 ## How to use
 
```
git clone https://github.com/IshchenkoRoman/RTv1
cd RTv1
make
./RTv1 data.obj
```

data.obj is included
In this .obj file you can change position, direction and color of object.



## Showtime

<img width="712" alt="screen shot 2017-11-30 at 9 29 47 pm" src="https://user-images.githubusercontent.com/30857998/34020573-f82d912e-e12c-11e7-836e-299a2ae94d4b.png">
<img width="712" alt="screen shot 2017-11-30 at 9 30 09 pm" src="https://user-images.githubusercontent.com/30857998/34020575-f905bc34-e12c-11e7-979f-ea9ab2a83494.png">
