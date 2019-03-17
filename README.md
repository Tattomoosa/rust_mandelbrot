# Asynchronous Mandelbrot Generator

Generates an image with a section of a mandelbrot set using user-defined criteria.
Small thing built while learning Rust, using a tutorial in the book "Programming Rust" by O'Reilly.

## Usage:

```
$ git clone git@github.com:Tattomoosa/rust_mandelbrot.git
$ cd rust_mandelbrot
$ cargo run mandel.png 2000x1500 -1.20,0.35 -1.0,0.20
```
Where the arguments are:
1. The output filename
2. Image dimensions in form "*width*`x`*height*"
3. Complex number at the top left, in form "*real*`,`*imaginary*"
3. Complex number at the bottom right "*real*`,`*imaginary*"
