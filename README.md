# Stackable3d
Project is a 3D LED CUBE DISPLAY (8x8x8 PIXELS) which displays different patterns stored in the **Microcontroller**. This LED cube is like a
LED screen, but what's special in that it has a third dimension, making it 3D. Think of it as many transparent low resolution displays. 

In normal displays it is normal to try to stack the pixels as close as possible in order to make it look better, but in
a cube one must be able to see through it, and more spacing between the pixels (actually it’s voxels since it is in 3d) is needed. The spacing is a
trade-off between how easy the layers behind it are seen, and voxel fidelity. Since it is a lot more work
making a LED cube than a LED display, they are usually low resolution. A LED display of 8x8 pixels are only 64 LEDs, but a LED cube in 8x8x8 is
512 LEDs, an order of magnitude harder to make! This is the reason LED cubes are only made in low resolution. A LED cube does not have to be symmetrical; it is possible to make a 7x8x9, or even oddly shaped ones. Here we have an 8x8x8 shaped one. 
The code is written in the**C language** using **AVR studio** and it is burned into the **ARDUINO** using the pony prog 2000.The circuit needs to be
mounted on the mechanical structure or platform where it displays the patterns that are stored in the arduino as indicated in the codes. The patterns are
displayed on a 3D structure which is made up of stainless steel rods. The messages can be changed 4 as per user need by rewriting the arduino in-built
memory. The complete display system circuit is power supply run on 5V, 2A which is provided externally
