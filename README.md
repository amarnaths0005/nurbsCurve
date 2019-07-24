# nurbsCurve
HTML Application to draw and modify a NURBS Curve in 3D

NURBS Curve = Non Uniform Rational B-Spline Curve

Requirements:
   1. Should enable the user to modify the x, y, z coordinates of the up to 20 control 
       points constituting a NURBS Curve.
       The range for coordinates of the control points should be [-1,1]. The user should 
       be able to modify these through sliders.
   2. Should display the NURBS Curve on the screen, and this curve should 
      change dynamically as the user modifies any of the values using sliders. 
      Perspective View. 
   3. Should display the bounding box of dimension 2 units, centred at the origin.
   4. Should enable the user to modify the camera angle (degrees), from which 
      viewing is done.
   5. Should enable the user to modify the u values of a chosen point, and should 
      display a moving point on the curve as the user modifies these values 
      using the sliders.
   6. All user input should be via sliders.
   7. Should use WebGL, in the form of three.js. 

Please report issues to amarnaths.codeproject@gmail.com

Open the file <i>index.html</i> in your browser.

Screenshot

![Screenshot of NurbsCurve](https://github.com/amarnaths0005/nurbsCurve/blob/master/nurbsCurve.png)
