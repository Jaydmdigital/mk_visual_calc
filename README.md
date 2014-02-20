#mini Kossel visual calculator#
==============

Using OpenSCAD, some mini Kossel STL files, some trig, and some color coding I have been working on creating a visual calculator for the mini Kossel.

What it needs for input:
```
  frame_extrusion_l = 240; //length of extrusions for horizontals, need cut length
  frame_extrusion_h = 600; //length of extrusions for towers, need cut length
  frame_extrusion_w = 15;  // width of extrusion. 
```
You can modify this and use different STL made for 20mm, but you need to change a lot of values based on openscad values in those files too.
```
  rail_depth = 13 // the overall height of your rail. 
```
Ths is a variable you should play with to see the impact it has. The bigger the depth, the shorter your diagonal rods need to be. Of course the belts still need to line up with the extrusions so there is a limit. 13 is the mgn12 height, you should consider this as a minimum
```
  rail_length = 400; // it needs this to kow where to place the max endstop switch mount and lower endstop for rails.
``` 
It uses this length to calcualate the maximum z height



