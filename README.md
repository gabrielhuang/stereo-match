Variational Stereo Matching
====

This notebook is a standalone implementation of the variational stereo-matching algorithm described in
```Pock, Thomas, et al. "A convex formulation of continuous multi-label problems." 
Computer Vision–ECCV 2008. Springer Berlin Heidelberg, 2008. 792-805.``` [Link to PDF](http://vision.in.tum.de/_media/spezial/bib/pock_et_al_eccv08.pdf)

Requirements
----
- NumPy
- SciPy
- Matplotlib

Description
----

The notebook reads a pair of left and right images, and the ground-truth disparity map.
It then minimizes a functional using a primal-dual proximal point method to infer the disparity map.
The cost to minimize is plotted as well as the distance to the ground-truth and various statistics to monitor convergence.
