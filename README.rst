COLLADA 1.5 Robot Models Repository
===================================

https://github.com/rdiankov/collada_robots

This repository is associated with the Open Robotics Automation Virtual Environment (OpenRAVE).

For more information, see:

http://openrave.org/docs/latest_stable/robots_overview/

The manipulatorlist file describes all the robots that have arms and can possibly be used in manipulation.

These files are separate from the openrave trunk since they can make the official releases very big. Users interested in using these files should set the OPENRAVE_DATA environment variable to point to this folder. In Linux add the following line in ~/.bashrc:

.. code-block:: bash

  export OPENRAVE_DATA=$OPENRAVE_DATA:${THIS FOLDER}
