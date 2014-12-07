===================
Parametric Surfaces
===================

*Class Library

###Description

Parametric Surfaces is a class library for 
This library of python classes could be used by the python scripting engine in Rhinoceros, Grasshopper, Autodesk Maya and Blender. Discussions for help on using these scripts can be found soon at: http://www.algitecture.com/


###Related Work

Surprisingly there is very little about the explicit computer-aided visualization of surfaces in Cartesian coordinates written in python or other scripting languages. The most important contribution might be the work by mathworld wolfram network [1] and Jürgen Meier [2].

###Contribution

In this library is presented a number of algorithms for computing 3D models for surfaces classes as Surface of Revolution, Minimal Surfaces based on given branch points, which could be used for generetion in CAD Systems.


###How it works

The two dimensional surfaces have representation in tree dimensional space. The parametric_ equation ...


###How to use it

Let's implement an example from the introduction::

	#!/usr/bin/env python
	import rhinoscriptsyntax as rs
	import RuledSurfaces as rsrf
	plueckerconoid=rsrf.AddPoints( rsrf.plueckerconoid_pts()  )

More examples soon on http://www.algitecture.com/


####Authors

Dimitry Demin - https://github.com/2D post.ddemin@gmail.com

####Why Python

Python 

####Acknowledgments

Thanks to Maxim Litvak_, Denis Petrov_.


####Legal Stuff

Copyright (c) 2014 Dimitry Demin. All Rights Reserved.

###TO DO
Add the calculation of tangent plane at the point with given parameters.

#####Note
This library is writen fast, feel free to change and add nessesar comments or propose (pull) changes. Mathematicians are welcome for any kind of proposal.

Literature:
-----------
1. http://mathworld.wolfram.com/, 14 Sept. 2014
2. http://www.3d-meier.de/, 14 Sept. 2014
3. Greene, B.; String Theory on Calabi-Yau Manifolds; http://arxiv.org/abs/hep-th/9702155; 1997-2014
4. http://mathworld.wolfram.com/topics/RuledSurfaces.html
5. http://www.3d-meier.de/tut3/Seite0.html
6. http://en.wikipedia.org/wiki/List_of_surfaces
http://www.indiana.edu/~minimal/research/claynotes.pdf
http://en.wikipedia.org/wiki/Minimal_surface
http://page.mi.fu-berlin.de/polthier/articles/diri/diri_jem.pdf
http://bugman123.com/Programs/index.html
http://paulbourke.net/geometry/
http://google-styleguide.googlecode.com/svn/trunk/pyguide.html


ParametricSurfaces © 2014 Dimitry Demin. All Rights Reserved.

...

.. _Litvak: https://github.com/maxlit
.. _Petrov: https://github.com/denpetrov
.. _parametric: http://mathworld.wolfram.com/ParametricEquations.html




