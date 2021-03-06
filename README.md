Tutorial on Impedance Control
=============================

This tutorial will guide you through the use of the [`remotecontrolboardremapper`](http://www.yarp.it/classyarp_1_1dev_1_1RemoteControlBoardRemapper.html) YARP device and the 
iDynTree classes [`iDynTree::Model`](http://robotology.gitlab.io/docs/idyntree/master/classiDynTree_1_1Model.html), 
[`iDynTree::ModelLoader`](http://robotology.gitlab.io/docs/idyntree/master/classiDynTree_1_1ModelLoader.html) 
and [`iDynTree::KinDynComputations`](http://robotology.gitlab.io/docs/idyntree/master/classiDynTree_1_1KinDynComputations.html) for whole-body control. 

The code contained in this example will show how to create a simple whole-body impedance controller.
The robot controlled in this way will try to keep its initial configuration even in presence of external disturbances while mantaining a compliant behaviour.

The control implements the following equation:
![controller](misc/controller.png)

# [How to complete the assignment](https://github.com/vvv-school/vvv-school.github.io/blob/master/instructions/how-to-complete-assignments.md)
