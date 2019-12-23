# render

wherein I build 3D rendering tools in Carp, based on [this book](https://www.gabrielgambetta.com/computer-graphics-from-scratch/).

## Raytracer

I built a simple software raytracer with

- ambient, point, and positional light,
- spheres as shapes (which is lame, I know),
- shadows,
- reflection, and
- varying opacity (without refraction for now).

It’s very simple and just about 150 lines of Carp, including the final dumping
into a PPM file (I was using SDL at first, but rendering in SDL based on points
is extremely slow).

Here’s an unexciting example picture:

![](/raytracer/rendered/ex1.png)

## Rasterizer

TODO

<hr/>

Have fun!
