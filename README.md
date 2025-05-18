# FractOL - Fractal Explorer

FractOL is a fractal visualization program that allows you to explore Mandelbrot and Julia sets using the MinilibX graphics library.

## Features

- Interactive visualization of the Mandelbrot fractal
- Julia set rendering with interactive parameter control
- Zoom in/out with mouse wheel
- Pan around using arrow keys
- Adjust iteration depth with +/- keys
- Real-time Julia set parameter adjustment by mouse movement

## How to Use

### Compilation

Compile the project using the provided Makefile:

```sh
make
```

### Running the Program

To view the Mandelbrot set:

```sh
./fractol mandelbrot
```

To view a Julia set (requires two parameters for the complex constant):

```sh
./fractol julia 0.285 0.01
```

###
