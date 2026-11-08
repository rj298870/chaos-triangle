# chaos-triangle
I made a page where you can zoom into the mandelbrot set and watch a sierpinski triangle draw itself out of random dots. It runs in your browser, so you dont have to install anything.
# what it draws
mandelbrot set. Every pixel is a number c. I start at z = 0 and keep doing z = z squared + c. If z gets farther than 2 from the middle it flies off forever so I stop and color the pixel by how many steps it took. If it never flies off the pixel is black.
