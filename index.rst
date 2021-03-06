RPy2 文档
======================


.. ifconfig:: release.endswith('dev') or release[:-1].endswith('alpha')

   .. warning::
      这份文档适用与rpy2的2.3版本。\
      现在的rpy2所提供的API还会随着时间变化，但是当前发布的版本已经可以满足大量应用的需求。\
      我们确信当前的版本要比2.1.X分支更好。
      
      即使我们一直关注各种功能性的问题，并且及时的更新文档，但是总会难免产生一些错误：\
      希望您能理解，RPy2仍在开发之中。


.. only:: html

   The first section contains a quick introduction, as well as how to get started
   (requirements, install rpy2). This should be the natural place to
   start if you are new to R, or rpy2. Hints for porting existing code to a newer
   version of rpy2 are also given.

   .. toctree::
      :maxdepth: 3

      getting-started
      porting-to-rpy2

   The high-level interface in rpy2 is designed to facilitate the use of R by
   Python programmers. R objects are exposed as instances of Python-implemented
   classes, with R functions as bound methods to those objects in a number of cases.
   This section also contains an introduction to graphics with R: *trellis* (*lattice*)
   plots as well as the grammar of graphics implemented in *ggplot2* let one
   make complex and informative plots with little code written, while the underlying
   *grid* graphics allow all possible customization is outlined.

   .. toctree::
      :maxdepth: 3

      high-level
   
   R is often used in a read-eval-print loop (REPL), where interactivity is important.
   Utilities are available in a dedicated sub-package.

   .. toctree::
      :maxdepth: 3

      interactive

   Users of the Python signature numerical package :mod:`numpy` can continue using
   the data structures they are familiar with, and share objects seamlessly with R.

   .. toctree::
      :maxdepth: 3

      numpy

   A lower-level interface, closer to R's C-level API, is available. It can be used
   when performance optimization is needed, or when extensions to the high-level
   interface are developped.

   .. toctree::
      :maxdepth: 3

      rinterface

   Finally, the documentation covers the subpackage with R-like Python classes
   and functions, callback functions, as well as compatibility with rpy-1.x.
   and benchmarks.

   .. toctree::
      :maxdepth: 3

      rlike
      miscellaneous


   The list of changes across versions can be helpful when
   upgrading to a newer version of rpy2.

   .. toctree::
      :maxdepth: 2

      appendix


.. only:: latex

   .. toctree::
      :maxdepth: 2

      getting-started
      high-level
      interactive
      numpy
      rinterface
      rlike
      miscellaneous

      appendix


