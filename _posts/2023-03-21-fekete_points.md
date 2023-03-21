---
title: 'Fekete Points'
date: 2023-03-21
permalink: /posts/2023/03/fekete_points/
---

Interpolation is an important problem, and doing interpolation requires interpolation points.

In one dimension, the Chebyshev points are well known and behave excellently, especially with barycentric Lagrange interpolation. The Chebyshev points are optimal in some sense, and they are the Lebesgue points for intervals of real numbers. Lebesgue points for more general domains are not known, and there doesn't seem to be any feasible way of calculating them. A tractable alternative to the Lebesgue points are the Fekete points, which are the points that maximize the determinant of the Vandermonde matrix. For n dimensional cubes, these points are given as the tensor product of the Chebyshev points and all works well. However, for a triangle, once again, the Fekete points are not known. There is [previous work](https://epubs.siam.org/doi/10.1137/S0036142998337247) that discusses the computation of the Fekete points on a triangle, but their computational method has the drawback of being slow. There is [other work](https://www.sciencedirect.com/science/article/pii/S0045782519301203) that discusses a faster method of finding these points, by starting with some non-uniform points. However, this approach seems to have problems as well.

I use an alternative approach. We start with equidistant points: ![equally spaced points](/images/equipoints.png)

Then, to get our interpolating points out of these, we apply the function that we use to go to Chebyshev nodes to each barycentric coordinate and then normalize, resulting in points moving towards the corners, similar to how Chebyshev points behave: ![better points](/images/fekepoints.png)

We then use this set of points to perform interpolation. To test them, we pick a Runge type function: ![function plot](/images/testinterpfunc.png)

Then, we interpolate:
![interpolation with equally spaced points](/images/equiinterp.png)
![interpolation with uneven points](/images/fekeinterp.png)

and we can look at the absolute errors:
![interpolation error with equally spaced points](/images/equierror.png)
![interpolation error with uneven points](/images/fekeerror.png)

and we see that the unevenly spaced points behave substantially better. We can also look at how the error scales in the interpolation degree:
![interpolation scaling with even and uneven points](/images/errorscaling.png)

so these are good points to interpolate on triangles with. 
