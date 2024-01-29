# DARPA-SUBOFF-DTRC-MATLAB
The Process uses MATLAB/Rhino/Grasshopper to automatically generates DARBA SUBOFF DTRC Model 5470 &amp; 5471 Bare Hull and Appendages with all possible configurations with variable surface quality using the equations provided from defense technical information center at their openly published website 
The source for the geometry characteristics is
https://apps.dtic.mil/sti/citations/ADA210642

in Matlab 
1.the Code will generate the Points and plot the surface inside matlab which can be used for CFD Hardcoded in MATLAB or other purposes
2.Create CSV File with x,y,z (which will be used to create surface in Rhino or any 3D Modeling Software)

in Rhino 
you will only use the import file command for CSV files and a few commands, grasshopper will do mostly everything

in Grasshopper 
1. you will assign the points to the node named point
2. grasshopper will generate the surface inside Grasshopper
3. Press Bake at the Surface Node to Create Actual Surface in Rhino

Detailed Process is Available at the DOCUMENTATION file
