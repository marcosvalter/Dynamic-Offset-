# Dynamic-Offset-
Dynamic Offset Macro for Fanuc five axis CNCs

Abstract
Dinamic offsets is a concept to solve posicion problems in 4 or 5 axis milling mchines.
At any new position of the 4th or 5th axis, the offsets X,Y and Z must be recalculated.

Implementation
A sphere coordinate system is used to calculate the position. Anny point defined by the offsets X,Y,Z, with distance to origin greater then zero, is a point in a sphere surface, with center in X0,Y0,Z0
Just need to calculate the Polar and Azimuthial angles, radius of sphere and calculate the new position.

Limitations
IMPORTANT: This macro only works with zero offset on the Polar axis, the one that does not rotate 360º.

VERY IMPORTANT
Use this at your own risc. This macro was not tested yet, and may need some adjustments, depending of your machine
