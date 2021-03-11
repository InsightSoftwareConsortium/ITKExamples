Flip An Image Over Specified Axes
=================================

.. index::
  single: FlipImageFilter
  single: flip


Synopsis
--------

Flip an image over the specified axes.  Pixels are swapped over the given axis.


Results
-------

.. figure:: Yinyang.png
  :scale: 50%
  :alt: Input image

  Input image

.. figure:: OutputBaseline.png
  :scale: 50%
  :alt: Output image

  Output image


Code
----

Python
......

.. literalinclude:: Code.py
   :language: python
   :lines: 1, 16-

C++
...

.. literalinclude:: Code.cxx
   :lines: 18-


Classes demonstrated
--------------------

.. breathelink:: itk::FlipImageFilter
