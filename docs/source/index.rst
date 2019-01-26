.. TOPP-RA documentation master file, created by
   sphinx-quickstart on Sat Nov 18 00:03:54 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

TOPP-RA: Fast path-parameterization for robots
===================================================

TOPP-RA is a library for computing :ref:`path parametrizations
<path-parametrization>` for arbitrary robot geometric
paths/trajectories. It can account for several types of constraints:

1. joint torque, velocity and acceleration bounds;
2. *robust* joint torque, velocity and acceleration bounds;
3. Cartesian acceleration bounds;
4. contact stability for legged robots.
5. Your constraint! See the tutorials to understand how to implement
   your own constraints and handle them with TOPP-RA.

For a given path, TOPP-RA can compute both its *time-optimal* path
parametrization as well as a time-parametrization with a *specified
duration*.

TOPP-RA is efficient. For standard use cases, it should return a
solution in 5ms-10ms.

  
See below for some tutorials, modules reference and installation
instructions.

.. toctree::
   :maxdepth: 2

   tutorials
   hello
   installation

.. _path-parametrization:
   
Why computing path parametrizations?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
TODO 

Cite TOPP-RA
~~~~~~~~~~~~~
If you use this library for your research, we encourage you to 

1. reference the accompanying paper `«A new approach to Time-Optimal Path Parameterization based on Reachability Analysis» <https://arxiv.org/abs/1707.07239>`_ *IEEE Transactions on Robotics*, vol. 34(3), pp. 645–659, 2018.
2. put a star on this repository!


Bug reports and supports
~~~~~~~~~~~~~~~~~~~~~~~~~
Please report any issues, questions via `Github issues tracker <https://github.com/hungpham2511/toppra/issues>`_.


qpOASES error codes
~~~~~~~~~~~~~~~~~~~~~

37: RET_INIT_FAILED_INFEASIBILITY

