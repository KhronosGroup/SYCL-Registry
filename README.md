# SYCL-Registry

The SYCL-Registry repository contains the SYCL C++ programming model for
OpenCL, including specifications.

It is also used as a backing store for the web view of the registry at
https://www.khronos.org/registry/sycl ; commits to the master branch of
this repository will be reflected there.

In the past, the SYCL registry was maintained in a public Subversion
repository. The history in that repository has not been imported to github,
but it is still available at
https://cvs.khronos.org/svn/repos/registry/trunk/public/sycl .

Interesting files in this repository include:

* index.php - toplevel index page for the web view. This relies on PHP
  include files found elsewhere on www.khronos.org and so is not very useful
  in isolation.
* specs/ - SYCL specification documents.
