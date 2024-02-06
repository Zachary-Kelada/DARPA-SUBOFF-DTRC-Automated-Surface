# DARPA-SUBOFF-DTRC-MATLAB
The Process uses MATLAB/Rhino/Grasshopper to automatically generates DARBA SUBOFF DTRC Model 5470 & 5471 Bare Hull and Appendages with all possible configurations with variable surface quality using the equations provided from defense technical information center at their openly published website The source for the geometry characteristics is  [https://apps.dtic.mil/sti/citations/ADA210642](https://apps.dtic.mil/sti/citations/ADA210642)
 
----
Full Model
![](https://raw.githubusercontent.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/main/README%20Pictures/1.png)

Bare Hull in Matlab
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/2.png?raw=true)

Hull Sail
| ![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/3.png?raw=true) |![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/4.png?raw=true)  |
|--|--|
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/5.png?raw=true) |![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/6.png?raw=true)  |) |![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/4.png?raw=true)  |

Sail in Rhino
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/7.png?raw=true)

Tail in Matlab
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/8.png?raw=true)
Tail in Rhino
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/9.png?raw=true)
Ring Wing Profile in Matlab
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/10.png?raw=true)
Ring Wing in Rhino
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/11.png?raw=true)
Ring Wing Strut in Matlab
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/12.png?raw=true)
Ring Wing with the Struts in Rhino
![](https://github.com/Zachary-Kelada/DARPA-SUBOFF-DTRC-Automated-Surface/blob/main/README%20Pictures/13.png?raw=true)


---
## in Matlab 
1.the Code will generate the Points and plot the surface inside matlab which can be used for CFD Hardcoded in MATLAB or other purposes 2.Create CSV File with x,y,z (which will be used to create surface in Rhino or any 3D Modeling Software)

## in Rhino
 (Make sure to change Rhino Tolerances) you will only use the import file command for CSV files and a few commands to turn points into curves and surfaces,

## in Grasshopper (still under development)

1.  you will assign the points to the node named point
2.  grasshopper will generate the surface inside Grasshopper
3.  Press Bake at the Surface Node to Create Actual Surface in Rhino

Detailed Process is Available at the DOCUMENTATION file
