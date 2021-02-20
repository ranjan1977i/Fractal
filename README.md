# Fractal

## Learning Objectives

* Showing Different Fractals with DPC++

* Understand the __Data Parallel C++ (DPC++)__ language and programming model


## Fractals and Mandelbrot
It is one of the most amazing discoveries in the realm of mathematics that not only does the simple equation Zn+1 = Zn2 + C create the infinitely complex Mandelbrot Set, but we can also find the same iconic shape in the patterns created by many other equations. In fact, the phenomenon of Mandelbrot Universality means that anytime we iterate a function that in some portion, at some scale, resembles the parabolic function Z2, then we will find small copies of the Mandelbrot Set in the map of that function.

### oneAPI Distribution
Intel&reg; oneAPI toolkits are available via multiple distribution channels:
* Local product installation: install the oneAPI toolkits from the __Intel® Developer Zone__.
* Install from containers or repositories: install the oneAPI toolkits from one of several supported
containers or repositories.
* Pre-installed in the __Intel® DevCloud__: a free development sandbox for access to the latest Intel® SVMS hardware and select oneAPI toolkits. 

## Tricorn(The Conjugate of mandelbrot)
Conjugate of mandelbrot
the tricorn, sometimes called the Mandelbar set, is a fractal defined in a similar way to the Mandelbrot set, but using the mapping 

Conj(Z^2 + C)

Where Z is the complex number


<img src="mandelbrot.png">

## Run

! chmod 755 q; chmod 755 run_simple.sh;if [ -x "$(command -v qsub)" ]; then ./q run_simple.sh; else ./run_simple.sh; fi

##
Optimized for GPU
